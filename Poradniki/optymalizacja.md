# Prosty poradnik jak zoptymalizować serwer Minecarft
Jeżeli twój serwer nie działa tak szybko, jak na jego możliwośći, możesz skorzystać z naszych propozycji aby zoptymalizować serwer.
### Spis treści:
- [Zoptymalizowane pliki](#Zoptymalizowane-pliki)
- [Wygenerowanie mapy](#spigot-i-jego-forki)
  - [Forge](#forge)
  - [Sponge](#sponge)
- [Zrobienie Timingów serwera](#Zrobienie-Timingów-serwera)

# Zoptymalizowane pliki

Podstawą zrobienia dobrego serwera Minecarft są dobrze zoptymalizowane pliki 
Gotowe pliki (bukkit.yml, spigot.yml, paper.yml, purpur.yml) znajdziesz [tutaj](https://mclist.io/resource/optimized-1-16-5)!
---
Należy wgrać je na serwer i zrestartować go.
# Wygenerowanie mapy

Minecraft jest grą z losowo generowanym, masywnym światem - jego granice sięgają aż ±30 000 000 długości i szerokości oraz 0-255 wysokości. Wygenerowanie tak dużego świata trwałoby wiele godzin (być może dni), nawet na najszybszych domowych komputerach. Dlatego Mojang zdecydował się na **generowania chunków** (klastrów 16x16x256 bloków) w miare, **jak gracze się do nich zbliżają**.

O ile w grze single-player ma to małe znaczenie, to na serwerze kilku-kilkunastu graczy eksplorujących świat powoduje, że generator chunków znacznie **obciąża CPU** i w konsekwencji **spadek TPS**. By temu zapobiec wystarczy przed **rozpoczęciem zabawy wygenerować obszar świata o rozmiarze odpowiadający naszym potrzebom**.

Mapa o rozmiarze 8 000 x8 000 bloków powinna w zupełności wystarczyć pod Survival na 20+ graczy.** Przy tych parametrach, zakładając 20 graczy, na każdego przypada średni wycinek mapy skłądający się z 1 780x1 780 bloków - 12 500 chunków. Dodatkowo, bez problemu można tę powierzchnię w przyszłości powiększyć.

---
### Zanim zaczniesz
1. Proces generowania mapy powoduje lagi w trakcie jego trwania i trwa bardzo długo - nawet 3 godziny. Dlatego warto to zrobić przed otwarciem serwera.
2. Mapę można wygenerować też **na domowym komputerze** a potem wgrać ją na serwer **przez FTP**. Trwa to nieporównywalnie krócej. Wystarczy podążać za instrukcjami dla **[Forge](#forge)** lub (dla wersji 1.13+) tutorialem z **[tego filmu](https://www.youtube.com/watch?v=5yRnGpcIoS8).** Z doświadczenia jednak wiemy, że dla wielu osób wrzucenie mapy na serwer jest problematyczne - opcja ta jest więc niepolecana.
3. **Uwaga! Puste (bez graczy) serwery Craftserve są usypiane. Przez cały okres generowania mapy należy mieć otwartą konsolę serwera w panelu Craftserve - to zapobiegnie jego uśpieniu.**
---

# Spigot i jego forki

### 1.14 i wyżej
Aby wykonać proces generowania świata, wystarczy ściągnąć i zainstalować **plugin [ChunkMaster](https://www.spigotmc.org/resources/chunkmaster.71351/)**. Jego obsługa jest bardzo prosta (parametry w `<>` są obowiązkowe, w `[]` opcjonalne):

* `/chm generate <mapa> <promien>` - ustala granicę świata **wyśrodkowaną na Twojej postaci**, gdzie `<mapa>` jest nazwą świata (najczęściej `world`), a `<promien>` ilością kratek wygenerowanych w każdą stronę.
* `/chm resume` - Uruchamia proces generowania świata (domyślnie świat nie generuje się kiedy na serwerze znajdują się gracze).
---
### Starsze wersje
Aby wykonać proces generowania świata, wystarczy ściągnąć i zainstalować **plugin [WorldBorder](https://www.spigotmc.org/resources/worldborder.60905/)**. Jego obsługa jest bardzo prosta (parametry w `<>` są obowiązkowe, w `[]` opcjonalne):

* `/wb set <promienX> [promienZ]` - ustala granicę świata **wyśrodkowaną na Twojej postaci**, gdzie `<promienX>` jest promieniem w osi X, a `<promienZ>` w osi Z - oba **wyrażone w blokach**. Jeśli `promienZ` nie będzie podany, użyta zostanie wartość `promienX`.
* `/wb shape <elliptic|rectangular>` - pozwala wybrać kształt granicy. `elliptic` to eliptyczna/okrągła, `rectangular` - prostokątna.
* `/wb fill [częstotliwość]` - rozpoczyna generowanie chunków z domyślną częstotliwością 20 prób na sekundę. Dla serwerów Grass należy ją zmniejszyć do 5. Na serwerach Diamond można spróbować nawet wartość 100. **Im mniejsza wartość, tym mniejsze lagi w trakcie generowania świata, ale też dłużej to trwa.**
* `/wb fill confirm` - komenda ta jest potrzebna do potwierdzenia rozpoczęcia `/wb fill`.

---

## Forge
Pregenerowanie mapy na serwerach **Forge** jest odrobinę bardziej skomplikowane, ponieważ mody ingerujące w wygląd świata niekoniecznie są ze sobą kompatybilne.
---
### Wersje od 1.10 do 1.12.2

**Jeśli na Twoim serwerze jest już zainstalowany [OpenTerrainGenerator](https://www.curseforge.com/minecraft/mc-mods/open-terrain-generator)** wystarczy, że uruchomisz generowanie komendą: 

`/otg pregen 150` - wygeneruje ona obszar o promieniu 150 chunków, co przekłada się na około 4800x4800 bloków.


**Jeśli nie masz zainstalowanego OTG** bezpieczniejszą opcją będzie [**Chunk-Pregenerator**](https://www.curseforge.com/minecraft/mc-mods/chunkpregenerator):

`/pregen gen startradius circle 0 0 150` - wygeneruje kolisty obszar o promieniu 150 chunków. Jeśli wolisz kształt kwadratu, zamiast `circle` wpisz `square`.

*Oba pluginy zainstalowane na kliencie Forge Minecrafta dodadzą graficzny interfejs ułatwiający ich obsługę.*
---
### Wersje od 1.6 do 1.7.10
---
Te, dość stare wersje, oferują jedynie plugin **[Admin Command Toolbox](https://www.curseforge.com/minecraft/mc-mods/admin-commands-toolbox)**, który nie posiada graficznego interfesju. Do poprawnego działania należy też zainstalować **[Mobius Core](https://www.curseforge.com/minecraft/mc-mods/mobiuscore)**.

By wygenerować świat należy wpisać:

`/pregenspawn 150` - co wygeneruje kwadrat o wymiarach 300x300 chunków - 150 każdą z 4 stron od spawnu.

<a name="sponge"><h2>Sponge</h2></a>

Na Sponge, natomiast, można wykorzystać odpowiednik pluginu Essentials - **[Plugin Nucleus](https://ore.spongepowered.org/Nucleus/Nucleus)**, którego szczegółowa dokumentacja znajduje się **[tutaj](https://nucleuspowered.org/)**.

Żeby wygenerować świat należy najpierw ustanowić jego granicę (którą można znieść po zakończeniu generowania) i rozpocząć proces:

* `/world border set <world> <x> <z> <srednica>` - gdzie `<world>` to nazwa naszego swiata, a `<x>` i `<z>` to koordynaty środka granicy.

* `world border gen -r <world>` - rozpoczyna tworzenie nowych chunków.

---
# Zrobienie Timingów serwera

Pierwszym krokiem jaki należy podjąć w przypadku problemów z lagami jest określenie ich natury - czy winna jest strona klienta, serwera czy może dostawca łącza internetowego.

Ticks per second
----------------
Domyślnie, serwer Minecraft jest zaprojektowany tak, że **w ciągu sekundy**, główna pętla gry wykonuje **20 cykli** (zwanych **tickami**) - jeśli tak jest, mówimy wtedy, że serwer ma **TPS=20**. Pod dużym obciążeniem może on jednak nie dać rady przeprowadzić obliczeń na czas, w związku z czym liczba cykli może spaść poniżej 20 i w takiej sytuacji mamy do czynienia z lagami serwerowymi.

By sprawdzić czy lagi są winą serwera użyj komendy **/tps** wyświetli Ci liczbę ticków na sekundę. Jeśli wartość ta jest mniejsza niż 20, znaczy to, że problem jest po stronie serwera, któremu obliczenia zajmują zbyt wiele czasu.

W przypadku **Sponge** jest to komenda **/sponge tps**, a dla **Forge** jest to **/forge tps**

Timings
--------

**Spigot** i **Paper** wyposażone są w bardzo przydatne narzędzie diagnostyczne jakim jest komenda **/timings**. **Bukkit** nie posiada tej, jak i wielu innych funkcji, dlatego zachęcamy do przesiadki na wcześniej wspomniane.

Jeśli chcesz dowiedzieć się czemu Twój serwer działa zbyt wolno, użyj komendy **/timings on**. Następnie, przez **co najmniej 10 minut, graj aktywnie** wykonując te same czynności co zwykle. Po tym czasie wpisz **/timings paste** - otrzymasz link do strony ze szczegółowymi (szczególnie w przypadku papera) statystykami.

Dla **Sponge** są to odpowiednio **/sponge timings on** oraz **/sponge timings paste**.

Tak uzyskany link możesz wkleić na nasz Discord, by uzyskać rady co do optymalizacji.

# Interpretacja

[**Jak samemu interpretować timingi** - SpigotMC](https://www.spigotmc.org/wiki/timings/)

[**Interpretacja timingów** - tłumaczenie autorstwa artur9010](https://ucraft.pl/forum/thread/188-czym-sa-i-jak-interpretowac-timmingi/)

*Zróło: https://github.com/craftserve/docs*
