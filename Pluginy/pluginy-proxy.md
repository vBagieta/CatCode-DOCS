# PlUGINY NA PROXY

## Spis Treści:
- [LuckPermsBungee](https://github.com/vBagieta/Minecraft/blob/main/Pluginy/pluginy-proxy.md#luckpermsbungee---menad%C5%BCer-globalnych-permisji)

- [SparkBungee](https://github.com/vBagieta/Minecraft/blob/main/Pluginy/pluginy-proxy.md#sparkbungee---kontrola-dzia%C5%82ania-serwera-proxy)


## Pluginy:

# LuckPermsBungee - Menadżer globalnych Permisji
Plugin pozwalający utworzyć grupy permisji dla graczy. Jeżeli nie użyjemy go na Proxy (Tylko na podserwerach), nikt nie będzie mógł używać komend (Permisji do pluginów) z Proxy. Aby wszystkie serwery wczytywały te same Permisje, musimy podpiąc je pod Baze Danych. [Pobierz](https://luckperms.net/download)

### Jak podpiąć Baze danych w LuckPermsie
Przejdź do katalogu głównego serwera, a następnie wyszukaj folder `Plugins`. Wejdź do katalogu Pluginu LuckPerms i otwórz plik `config.yml`.
Zlokalizuj ten fragment: i zacznij go edytować

`storage-method: MySQL #Do jakiej bazy danych Plugin będzie podpięty,  możesz użyc: MySQL, MariaDB, PostgreSQL, MongoDB`

`data:`

  `address: mysql.twojserwer.pl:3306 #Host Bazy Danych Uwaga! Host zawsze musisz zapisać jako host:port_bazy`

  `database: xyz #Nazwa Bazy danych`

  `username: ROOT #Nazwa użytkownika`
  
  `password: 'HasloMaslo' #Haslo logowania bazy danych`
  
# SparkBungee - Kontrola działania serwera Proxy
Spark to najlepszy plugin na kontrlowanie kondycji serwera.

Profiler procesora: diagnozuj problemy z wydajnością. 

Kontrola pamięci: Diagnozuj problemy z pamięcią. 

Raportowanie kondycji serwera: Śledź ogólną kondycję serwera. [Pobierz](https://spark.lucko.me/download)

