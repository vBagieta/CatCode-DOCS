# Spolszczenie pluginu [Bungee Staff](https://www.spigotmc.org/resources/%E2%AD%90%EF%B8%8F-bungeestaff-%E2%AD%90%EF%B8%8F-%E2%9C%85-discord-api-%E2%9C%85-infinite-chats-and-commands-%E2%9C%85-bungee-moderation-%E2%9C%85-1-7-1-18-%E2%9C%85.95425/) przez [vBagieta](https://github.com/vBagieta)


```
DEFAULT:
  PREFIX: '&f&lSTAFF> '
  NO-PERMISSIONS: '&cNie ma takiej komendy.'
  PLAYER-NOT-FOUND: '&cGracz <target> nie znaleziony.'
  ONLY-PLAYERS: '&cTylko gracze mogą użyć tej komendy.'
  OBJECTS:
    TRUE-ARGUMENT: '&awłączone'
    FALSE-ARGUMENT: '&cwyłączone'
SEARCH:
  SEARCH-FORMAT:
 - '[<chat_bar>](golden)'
  - '&fGracz &a<player> &fzostał &aznaleziony&f.'
  - '&fSerwer: &a<hover><server></hover>'
  - '[<chat_bar>](golden)'
  SEARCH-HOVER: '&7| &eKliknij aby dołączyć'
  SEARCH-COMMAND: /server <server>
SERVER-KICK:
  KICKED-MESSAGE: '&Zostałeś &cwyrzucony &fprzez administracje.'
  PLAYERS-KICKED: '&fWszyscy gracze na &c<server> &fzostali wyrzuceni.'
  SERVER-NOT-FOUND: '&fSerwer &c<server> &fnie znaleziony.'
STAFFS:
  LIST-FORMAT:
 - '[<chat_bar>](golden)'
  - '&6Administracja&f online:'
  - '&6<player> &7(<server>)'
  - '[<chat_bar>](golden)'
  JOIN: '&b<prefix><player> &7Dołączył na serwer.'
  LEFT: '&b<prefix><player> &7Opuścił serwer.'
  MOVE: '&b<prefix><player> &7Połaczył sie na &b<server>&7.'
COOLDOWN:
  HAVE-COOLDOWN: '&cZaczekaj &9<cooldown> &7sekund(s) do użycia komendy
    &bponownie&7.'
COMMANDS:
  COMMAND-TOGGLED: '&7Komendy wyjściowe ''&b<command>&7'' mają wartość <value>&7.'
  COMMAND-NO-EXIST: '&7Ta komenda nie istnieje&7.'
CHATS:
  CHAT-TOGGLED: '&7Chat ''&b<chat>&7'' ma wartość <value>&7.'
  CHAT-NO-EXIST: '&7Ten chat nie istnieje&7.'
ALIASES:
  TELEPORT: '&7Łaczenie z &b<server>&7.'
  ALREADY: '&cJesteś już połączony z tym serwerem.'
LIMBO:
  NOT-SET: '&7Limbo nie zostało skonfigurowane!'
  JOIN: '&7Dołączyłeś do Limbo. Poczekaj na ponowne połączenie z serwerem.'
  LEFT: '&7Wychodzisz z limbo.'
  MOVE-CANCELLED: '&7Nie możesez sie poruszać.'
  SERVER-REACHED: '&7Sewer <server> jest online. Za 15 sekund zostaniesz przeniesiony.'
  SERVER-NOT-REACHED: '&7Serwer <server> nie odpowiada. Trwa teleportacja do głównego serwera.'
