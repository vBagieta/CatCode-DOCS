# Poradnik konfiguracji serwera Proxy

Poradnik jest we wczesnym pisaniu, niedługo dodam więcej szczegółów.
# Instalacja

Udaj się na stronę [PaperMC](https://papermc.io/downloads) i pobierz najnowszą wersje silnika Waterfall.

Do katalogu głównego serwera wgraj silnik. Do poprawnego działania silnika, przydziel mu `1GB` pamięci RAM. 
Następnie włacz serwer, i sprawdź czy wszytko poprawnie się włączyło. Gdy upewnisz się, że wszytko dobrze się uruchomiło, czas przejść do konfiguracji.

# Konfiguracja

Silnik powinien wygenerować plik config.yml. Przejdź do tego pliku. 

## Dodawanie serwerów

Aby dodać do naszego Proxy serwer, w pliku config.yml zlokalizuj linijke servers.
Przykładowe zdefiniowanie serwera:
```
servers:
  NAZWA_SERWERA:
    motd: 'MOTD SERWERA'
    address: ADRESS_IP_NAJLEPIEJ_Z_PORTEM
    restricted: false
```

# Ustawienia

Uwaga! Ustawienia, których nie ma poniżej nie trzeba zmieniać!

```
server_connect_timeout: 5000 #Po jakim czasie serwer ma wywalać Timeout

forge_support: true #Czy na Proxy mogą łączyć się gracze przez Forge'a

player_limit: -1 #Limit graczy łączących się przez Proxy (-1 brak ograniczeń)

permissions:
  default:
  - bungeecord.command.server      #
  - bungeecord.command.list        # Ustawienia permsiji dla
  admin:                           # Danej grupy graczy.
  - bungeecord.command.alert       #
  - bungeecord.command.end         # Nie polecamy tej funkcji tutaj, 
  - bungeecord.command.ip          # Lepiej skorzystać z LuckPermsBungee
  - bungeecord.command.reload      #

online_mode: true #Czy serwer ma być tylko dla graczy Premium.

disabled_commands:
- disabledcommandhere #Wyłączone komendy

listeners:
- query_port: 25577 #Port, na którym serwer będzię się włączał

  motd: '&1Another Bungee server' #Motd wyświetlany na Proxy

  priorities:
  - NAZWA_SERWERA #Ustawienia serwerów
  - NAZWA_SERWERA_2 

  max_players: 1 #Ile maksymalnie graczy może wejść przez Proxy.

  force_default_server: false #Jeżeli to ustawimy, serwer z najwyższym piorytetem będzie tym głównym

ip_forward: false #Ta funkcja musi być włączona, jeżeli włączasz na podserwerach właczasz bungeecorda (bungeecord: true)

groups:
  md_5:
  - admin #Ustawianie grup dla graczy! 

log_pings: true #Czy w konsoli ma wyświetlać się log, gdy ktoś spinguje serwer?
```

# Pluginy

Instalacja pluginów na Proxy jest identyczna jak na serwerze spigotowym. Liste polecanych pluginów znajdziesz [tutaj](https://github.com/vBagieta/CatCode-DOCS/blob/main/Pluginy/pluginy-proxy.md)
