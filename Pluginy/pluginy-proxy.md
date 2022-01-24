# PlUGINY NA PROXY

## Spis Treści:
- [LuckPermsBungee](https://github.com/vBagieta/Minecraft/blob/main/Pluginy/pluginy-proxy.md#luckpermsbungee---menad%C5%BCer-globalnych-permisji)
  - [Podpinanie bazy danych](https://github.com/vBagieta/Minecraft/blob/main/Pluginy/pluginy-proxy.md#jak-podpi%C4%85%C4%87-baze-danych-w-luckpermsie)
- [SparkBungee](https://github.com/vBagieta/Minecraft/blob/main/Pluginy/pluginy-proxy.md#sparkbungee---kontrola-dzia%C5%82ania-serwera-proxy)

- [PlayerBalancer](https://github.com/vBagieta/Minecraft/blob/main/Pluginy/pluginy-proxy.md#playerbalancer---balansuj-graczy-pomi%C4%99dzy-serwerami)
  - [Zasady przełączania graczy](https://github.com/vBagieta/Minecraft/blob/main/Pluginy/pluginy-proxy.md#gracze-mog%C4%85-by%C4%87-prze%C5%82%C4%85czani-pomi%C4%99dzy-serwerami-za-pomoc%C4%85-zasad)

## Pluginy:

# LuckPermsBungee - Menadżer globalnych Permisji
Plugin pozwalający utworzyć grupy permisji dla graczy. Jeżeli nie użyjemy go na Proxy (Tylko na podserwerach), nikt nie będzie mógł używać pluginów z Proxy. Aby wszystkie serwery wczytywały te same Permisje, musimy podpiąc je pod Baze Danych. Kliknij [tutaj](https://luckperms.net/download) aby pobrać.

### Jak podpiąć Baze danych w LuckPermsie
Przejdź do katalogu głównego serwera, a następnie wyszukaj folder `Plugins`. Wejdź do katalogu Pluginu LuckPerms i otwórz plik `config.yml`.
Zlokalizuj ten fragment: i zacznij go edytować.
```
storage-method: MySQL #Do jakiej bazy danych Plugin będzie podpięty. (MySQL, MariaDB, PostgreSQL, MongoDB)

data:
  address: mysql.twojserwer.pl:3306 #Host Bazy Danych, zawsze musisz zapisać jako host:port_bazy
  database: xyz #Nazwa Bazy danych
  
  username: ROOT #Nazwa użytkownika
  password: 'HasloMaslo' #Haslo logowania bazy danych
  ```
  
# SparkBungee - Kontrola działania serwera Proxy
**Spark** to **najlepszy** plugin na kontrlowanie kondycji serwera, Plugin pobierzesz [tutaj](https://spark.lucko.me/download). 

- **Profiler procesora:** Możesz zdiagnozować problemy z działaniem CPU

- **Kontrola pamięci:** Możesz kontrolować stan pamięci RAM

- **Raportowanie kondycji serwera:** Możesz monitorować ogólny stan kondycji serwera

# PlayerBalancer - Balansuj graczami pomiędzy serwerami!

Posiadasz pare lobby, a gracze są przenoszeni tylko na jedno? Chcesz dodac komendy typu /lobby? A może chcesz aby graczy po wyrzuceniu z podserwera nie byli wyrzucani z sieci? Dobrze trafiłeś! To wszytko pozwala plugin PlayerBalancer! Dodatkowo wspiera Pluginy na [Party](https://www.spigotmc.org/resources/party-and-friends-for-bungeecord-supports-clients-from-1-7-to-1-9.9531/) oraz [Znajomych](https://www.spigotmc.org/resources/ultimate-friends.3964/)! Plugin pobierzesz [tutaj!](https://www.spigotmc.org/resources/playerbalancer.55011/updates)
### Gracze mogą być przełączani pomiędzy serwerami za pomocą zasad:
  - `NONE` - Gracz zostanie przełączony do serwera z którym się łączył.
  - `RANDOM` - Losowy serwer.
  - `RANDOM_LOWEST` - Losowy serwer z najmniejszą ilością graczy.
  - `RANDOM_FILLER` - Losowy serwer z największą ilością osób, ale nie pełny.
  - `PROGRESSIVE` - Pierwszy serwer który nie jest pełny.
  - `PROGRESSIVE_LOWEST` - Pierwszy serwer z najmniejszą ilością osób.
  - `PROGRESSIVE_FILLER` - Pierwszy serwer z największą ilośćią osób, ale nie pełny.
  - `EXTERNAL` - Przezuca gracza według innego pluginu.
