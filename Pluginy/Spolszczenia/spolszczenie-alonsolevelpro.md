# Spolszczenie pluginu [Alonso Level Pro]() przez [vBagieta](https://github.com/vBagieta)

```
#      _   _                  _                _      ___
#     /_\ | |___ _ _  ___ ___| |   _____ _____| |___ | _ \_ _ ___
#    / _ \| / _ \ ' \(_-</ _ \ |__/ -_) V / -_) (_-< |  _/ '_/ _ \
#   /_/ \_\_\___/_||_/__/\___/____\___|\_/\___|_/__/ |_| |_| \___/
#          https://www.spigotmc.org/resources/authors/281176/
#              Support server: alonsoaliaga.com/discord
#        Subscribe to my Youtube channel: alonsoaliaga.com/play
#          Subscribe to my Twitch: alonsoaliaga.com/twitch
# Thanks for purchasing my plugin! If you didn't purchase it then do it!
#                  Only buyers will receive support.
Messages:
  No-permission: "&cNie ma takiej komendy."
  Reloaded: "&aSome messages and options have been reloaded. Other may require a restart!"
  Invalid-player: "&cGracz nie jest online!"
  Invalid-amount: "&cAmount is not a valid number!"
  Invalid-negative-amount: "&cAmount is not a valid positive number!"
  Please-reconnect: "&cSomething went wrong. Please reconnect to the server!"
  Please-reconnect-other: "&cThe player is not registered. {PLAYER} must reconnect to the server!"
  Disabled-world: "&cYou cannot use this command in your current world."
  Game-mode-enabled: "&cYou cannot use this command while playing."
  Only-console: "&cFor security reasons this command can be executed in console only."
  Vault-disabled: "&cVault/economy is not enabled in this server."
  Help:
    Admin:
    - "&6 /level rewards <player> &f- &eOpen rewards for player"
    - "&6 /level stats <player> &f- &eCheck player stats"
    - "&6 /level reset <player> &f- &eReset player stats &c(Console only)"
    - "&6 /level addexp <player> <amount> &f- &eAdd experience to player"
    - "&6 /level addrandomexp <player> <min> <max> &f- &eAdd random experience to player"
    - "&6 /level removeexp <player> <amount> &f- &eRemove experience from player"
    - "&6 /level setexp <player> <amount> &f- &eSet player's experience"
    - "&6 /level addlevel <player> <amount> &f- &eAdd levels to player"
    - "&6 /level removelevel <player> <amount> &f- &eRemove levels from player"
    - "&6 /level setlevel <player> <level> &f- &eSet player's level"
    - "&6 /level addmoney <player> <amount> &f- &eAdd economy based on multiplier"
    - "&6 /level addrandommoney <player> <min> <max> &f- &eAdd economy based on multiplier"
    - "&6 /level reload &f- &eReload configuration"
    User:
    - "&6 /level rewards &f- &eZobacz nagrody za levele"
    - "&6 /level stats &f- &eZobacz swoje statystyki"
  Leaderboard:
    Signs:
      Level:
        Rank:
        - "&c--&e #{RANKING} &c--"
        - "&f{PLAYER}"
        - "&bLevel {SCORE}"
        - "&c-------------"
        None:
        - "&c--&e #{RANKING} &c--"
        - "&cNo player"
        - "&bUnknown"
        - "&c-------------"
      Experience:
        Rank:
        - "&c--&e #{RANKING} &c--"
        - "&f{PLAYER}"
        - "&b{SCORE} XP"
        - "&c-------------"
        None:
        - "&c--&e #{RANKING} &c--"
        - "&cNo player"
        - "&bUnknown"
        - "&c-------------"
  Placeholders:
    Multiplier:
      None: "&7{MULTIPLIER}"
      Multiplier: "&6{MULTIPLIER}"
    Additional-multiplier:
      None: "&e+&6{MULTIPLIER}"
      Multiplier: "&e+&6{MULTIPLIER}"
    Leaderboards:
      Level:
        No-name: "&7Unknown"
        No-score: "&7Unknown"
        Rank: "&e{RANKING}. &b{PLAYER} &7- &e{SCORE}"
        None: "&7No data available"
      Experience:
        No-name: "&7Unknown"
        No-score: "&7Unknown"
        Rank: "&e{RANKING}. &b{PLAYER} &7- &e{SCORE}"
        None: "&7No data available"
    Level:
      Format: "{LEVEL}✫"
      Format-color: "{COLOR}{LEVEL}✫"
    Rewards:
      Locked-color: "&c"
      Unlocked-color: "&a"
      Claimed-color: "&c"
  Auto-claim:
    No-permission: "&cYou cannot toggle this option. Purchase &a[RANK]&c rank in &bstore.yournetwork.net&c!"
    Enabled: "&aYou enabled auto-claim feature! Rewards will be claimed automatically now."
    Enabled-restricted: "&aYou enabled auto-claim feature, however this server has restricted auto-claiming.."
    Disabled: "&cYou disabled auto-claim feature! Rewards must be claimed manually now."
    #PlaceholderAPI is supported. Suggestion: Do not use AlonsoLevels placeholders here.
    Auto-claimed:
    - " "
    - "&6Pomyślnie odebrano &e{AMOUNT} &6Nagorde!"
    - " "
  Claim:
    Locked-reward: "&cNie możesz jeszcze odebrać tej nagrody!"
    Already-claimed-reward: "&cJuż odebrałeś tę nagrodę!"
    Claimed-reward: "&aOdebrałeś tę nagrodę!"
    Disabled-server: "&cNie możesz odebrać tej nagrody tutaj! Odbierz ją w {SERVER}."
  Add-exp:
    Cancelled: "&cYour action was cancelled by a plugin!"
    Added-exp: "&aYou added {EXPERIENCE} experience points to {PLAYER}."
    Notify: " &d+{EXPERIENCE} Dośwaidczenia!"
  Add-random-exp:
    Cancelled: "&cYour action was cancelled by a plugin!"
    Added-exp: "&aYou added {EXPERIENCE} experience points to {PLAYER}."
    Notify: " &8+&3{EXPERIENCE} YourNetwork Experience!"
  Remove-exp:
    Cancelled: "&cYour action was cancelled by a plugin!"
    Removed-exp: "&aYou removed {EXPERIENCE} experience points from {PLAYER}."
    Notify: " &c-{EXPERIENCE} Doświadczenia!"
  Set-exp:
    Cancelled: "&cYour action was cancelled by a plugin!"
    Set-exp: "&aYou set {PLAYER}'s experience to {EXPERIENCE}."
    Notify-add: " &d+{EXPERIENCE} Doświadczenia!"
    Notify-remove: " &c-{EXPERIENCE} Doświadczenia!"
  Add-level:
    Cannot-add-zero: "&cYou cannot add {LEVEL} levels to {PLAYER}."
    Added-level: "&aYou added {LEVEL} level(s) to {PLAYER}."
    Notify-add: " &6+{LEVEL} Level!"
    Notify-remove: " &c-{LEVEL} Level!"
  Remove-level:
    Cannot-remove-zero: "&cYou cannot add {LEVEL} levels to {PLAYER}."
    Removed-level: "&aYou removed {LEVEL} level(s) from {PLAYER}."
    Notify-add: " &8+&3{LEVEL} YourNetwork Level(s)!"
    Notify-remove: " &8-&3{LEVEL} YourNetwork Level(s)!"
  Set-level:
    Set-level: "&aYou set {PLAYER}'s level to {LEVEL}."
    Notify-add: " &6+{LEVEL} Level!"
    Notify-remove: " &c-{LEVEL} Level!"
  Reset:
    Cancelled: "&cYour attempt to reset {PLAYER}'s statistics was cancelled by a plugin."
    Player-reset: "&a&lYou reset {PLAYER}'s statistics! Player was kicked to save new data."
    #Reason to kick player to save data. Placeholders {PLAYER} playername, {UUID} player uuid
    #PlaceholderAPI is supported. However since the player just joined, it might not work correctly.
    Kick-reason:
    - "&fInternal Exception: java.io.IOException: An existing connection was forcibly closed by the remote host"
  Add-money:
    Invalid: "&cAmount must be a valid positive number."
    Invalid-zero: "&cAmount cannot be zero."
    Added: "&aYou added {COINS}&a to {TARGET}'s balance."
    Added-multiplier: "&aYou added {COINS}&6(+{BONUS} ⛃)&a to {TARGET}'s balance."
    Notify: "&e+{COINS} Monet"
    Notify-multiplier: "&e+{COINS} Monet &7(&e+{BONUS} &eOsobisty booster&7)"
    Error: "&cUnexpected error adding coins to {TARGET}. Error: {ERROR}"
  Add-random-money:
    Invalid: "&cAmounts must be a valid positive numbers."
    Invalid-zero: "&cMax amount cannot be zero."
    Added: "&aYou added {COINS}&a to {TARGET}'s balance."
    Added-multiplier: "&aYou added {COINS}&6(+{BONUS} ⛃)&a to {TARGET}'s balance."
    Notify: "&e+{COINS} &7Monet"
    Notify-multiplier: "&e+{COINS} Monet &7(+{BONUS} &eOsobisty booster&7)"
    Error: "&cUnexpected error adding coins to {TARGET}. Error: {ERROR}"
  Keys:
    Progress-bar:
      Amount: 10
      Character: "■"
      Complete: "&a"
      Remaining: "&7"
    Progress:
      Format: "&a{LEVEL_EXPERIENCE}&7/&b{REQUIRED_EXPERIENCE}"
      Max-level: "&c&lMAXYMALNY LEVEL"
      Max-level-short: "&c&lMAX LEVEL"
  Stats:
    #Supports PlaceholderAPI if available.
    Self:
    - "&6&l▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬&r"
    - "&r"
    - "              &6POSIADASZ &e&l{LEVEL} &6LEVEL"
    - "         &eTwój progres: &8[{PROGRESS}&8]"
    - "&r"
    - "  &6Obecne całkowite doświadczenie: &e&l{TOTAL_EXPERIENCE}"
    - "&r"
    - "&6&l▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬&r"
    #Supports PlaceholderAPI if available.
    Self-max-level:
    - "&6&l▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬&r"
    - "           &6&lTwoje statystyki!"
    - "             &c&lMAX LEVEL!"
    - "&r"
    - "  &eTwój aktualny level: &6&l{LEVEL}"
    - "  &ePoziom doświadczenia: &6&l{TOTAL_EXPERIENCE}"
    - "&6&l▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬&r"
    #Supports PlaceholderAPI if available.
    Other:
    - "&6&l▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬&r"
    - "          &6&lStatystyki {PLAYER}"
    - "&a "
    - "  &eAktualny level: &6&l{LEVEL}"
    - "  &enastępny level: &6&l{NEXT_LEVEL}"
    - "  &eProgres: &8[{PROGRESS}&8]"
    - "&b "
    - "  &eObecny poziom doświadczenia: &6&l{LEVEL_EXPERIENCE}"
    - "  &eDoświadczenie na wyższy poziom: &6&l{REQUIRED_EXPERIENCE}"
    - "  &eObecne całkowite doświadczenie: &6&l{TOTAL_EXPERIENCE}"
    - "&6&l▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬&r"
    #Supports PlaceholderAPI if available.
    Other-max-level:
    - "&6&l▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬&r"
    - "      &eStatystyki &6{PLAYER}"
    - "            &c&lMAX LEVEL!"
    - "&r"
    - "  &eAktualny level: &6&l{LEVEL}"
    - " &eAktualny poziom doświadczenia: &6&l{TOTAL_EXPERIENCE}"
    - "&6&l▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬&r"
  Level-up:
    #Leave "" to disable. Available placeholder: "{NEW_LEVEL}" replaced with new level.
    Title: "&6&lLEVEL UP"
    #Leave "" to disable. Available placeholder: "{NEW_LEVEL}" replaced with new level.
    Subtitle: "&r"
    #{CENTER} can be used here to attempt to center the message in THIS MESSAGE.
    Multiplier-unlocked: "&d{MULTIPLIER}x &eMnoznik monet &6&lOdblokowany!&7!"
    #{CENTER} can be used here to attempt to center the message in THIS MESSAGE.
    Max-level-reached: "              &6&lZdobyłeś MAXYMALNY LEVEL!!!"
    #{CENTER} can be used here to attempt to center the message in THIS MESSAGE.
    Open-rewards-not-spigot: "&eOtwórz menu nagród, aby je odebrać"
    #{CENTER} can be used here to attempt to center the message in THIS MESSAGE.
    Open-rewards-spigot: "              &eKliknij tutaj aby odebrać nagrody"
    Open-rewards-hover: "&eKliknij aby odebrać nagrody!"
    #{CENTER} can be used here to attempt to center the message in THIS MESSAGE.
    #This is a BETA feature and might not work properly.
    #Supports PlaceholderAPI is available.
    Message:
    - "&6&l▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬&r"
    - "                             &d&k0&r &e&lLEVEL UP! &d&k0&r"
    - "&r "
    - "                       &eMasz teraz Level &6&l{LEVEL}&e!"
    - "                        {MAX_LEVEL}"
    - "&r "
    - "                        {UNLOCKED}"
    - "                        {REWARDS}"
    - "&6&l▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬&r"

Inventories:
  Normal:
    Title: "&8Nagrody za levele"
  Veteran:
    Title: "&cNagrody najlepszego gracza!"

Items:
  Rewards:
    Normal:
      Locked:
        Material: "STORAGE_MINECART" #Supports "CUSTOM_HEAD"
        #Supported in 1.14+ ONLY if you wanna use a custom resource pack
        Custom-model-data: 0
        #Only available if material is CUSTOM_HEAD
        Texture: "eyJ0ZXh0dXJlcyI6eyJTS0lOIjp7InVybCI6Imh0dHA6Ly90ZXh0dXJlcy5taW5lY3JhZnQubmV0L3RleHR1cmUvZDVjNmRjMmJiZjUxYzM2Y2ZjNzcxNDU4NWE2YTU2ODNlZjJiMTRkNDdkOGZmNzE0NjU0YTg5M2Y1ZGE2MjIifX19"
      Unlocked:
        Material: "STORAGE_MINECART" #Supports "CUSTOM_HEAD"
        #Supported in 1.14+ ONLY if you wanna use a custom resource pack
        Custom-model-data: 0
        #Only available if material is CUSTOM_HEAD
        Texture: "eyJ0ZXh0dXJlcyI6eyJTS0lOIjp7InVybCI6Imh0dHA6Ly90ZXh0dXJlcy5taW5lY3JhZnQubmV0L3RleHR1cmUvYjJjNWY3YWM3MDZiMmU4YTg3OGViZjk3MmIwN2YzZDM2NDQ5YWI3MGIwOWFjZDk3M2VlYWJiMGQ1ZmM0YTZiNCJ9fX0="
      Claimed:
        Material: "MINECART" #Supports "CUSTOM_HEAD"
        #Supported in 1.14+ ONLY if you wanna use a custom resource pack
        Custom-model-data: 0
        #Only available if material is CUSTOM_HEAD
        Texture: "eyJ0ZXh0dXJlcyI6eyJTS0lOIjp7InVybCI6Imh0dHA6Ly90ZXh0dXJlcy5taW5lY3JhZnQubmV0L3RleHR1cmUvZDhjNTNiY2U4YWU1OGRjNjkyNDkzNDgxOTA5YjcwZTExYWI3ZTk0MjJkOWQ4NzYzNTEyM2QwNzZjNzEzM2UifX19"
    Veteran:
      Locked:
        Material: "TNT_MINECART" #Supports "CUSTOM_HEAD"
        #Supported in 1.14+ ONLY if you wanna use a custom resource pack
        Custom-model-data: 0
        #Only available if material is CUSTOM_HEAD
        Texture: "eyJ0ZXh0dXJlcyI6eyJTS0lOIjp7InVybCI6Imh0dHA6Ly90ZXh0dXJlcy5taW5lY3JhZnQubmV0L3RleHR1cmUvMTZiZDg3Y2Q4YzE0N2U3NmM1N2UxYmI1NDE1YmJjYzU0YjhjNDNjNTYxNzc2NzcyNTczMjNjZDI2OWFlNCJ9fX0="
      Unlocked:
        Material: "TNT_MINECART" #Supports "CUSTOM_HEAD"
        #Supported in 1.14+ ONLY if you wanna use a custom resource pack
        Custom-model-data: 0
        #Only available if material is CUSTOM_HEAD
        Texture: "eyJ0ZXh0dXJlcyI6eyJTS0lOIjp7InVybCI6Imh0dHA6Ly90ZXh0dXJlcy5taW5lY3JhZnQubmV0L3RleHR1cmUvYjZhY2ZjNjQzZjYwOGUxNmRlMTkzMzVkZGNhNzFhODI4ZGZiOGRhY2E1NzkzZWI1YmJjYjBjN2QxNTU5MjQ5In19fQ=="
      Claimed:
        Material: "MINECART" #Supports "CUSTOM_HEAD"
        #Supported in 1.14+ ONLY if you wanna use a custom resource pack
        Custom-model-data: 0
        #Only available if material is CUSTOM_HEAD
        Texture: "eyJ0ZXh0dXJlcyI6eyJTS0lOIjp7InVybCI6Imh0dHA6Ly90ZXh0dXJlcy5taW5lY3JhZnQubmV0L3RleHR1cmUvZDhjNTNiY2U4YWU1OGRjNjkyNDkzNDgxOTA5YjcwZTExYWI3ZTk0MjJkOWQ4NzYzNTEyM2QwNzZjNzEzM2UifX19"
    Locked-lore:
    - ""
    - "&cNie możesz tego odebrać!"
    Unlocked-lore:
    - ""
    - "&ekliknij aby odebrać!"
    Claimed-lore:
    - ""
    - "&aOdebrałeś już tą nagrode!"
  Multipliers:
    Locked:
      Material: "COAL_BLOCK" #Supports "CUSTOM_HEAD"
      #Supported in 1.14+ ONLY if you wanna use a custom resource pack
      Custom-model-data: 0
      #Only available if material is CUSTOM_HEAD
      Texture: "eyJ0ZXh0dXJlcyI6eyJTS0lOIjp7InVybCI6Imh0dHA6Ly90ZXh0dXJlcy5taW5lY3JhZnQubmV0L3RleHR1cmUvYmRhN2RmMGM2NzYxNjMwNWNlZTI5ZTRlYTJlMzQwNjE1NDYzNjY5NWVmZWY5ZmY3MzVlZmQwMDc0YjAwMjg0YSJ9fX0="
    Unlocked:
      Material: "GOLD_BLOCK" #Supports "CUSTOM_HEAD"
      #Supported in 1.14+ ONLY if you wanna use a custom resource pack
      Custom-model-data: 0
      #Only available if material is CUSTOM_HEAD
      Texture: "eyJ0ZXh0dXJlcyI6eyJTS0lOIjp7InVybCI6Imh0dHA6Ly90ZXh0dXJlcy5taW5lY3JhZnQubmV0L3RleHR1cmUvOTQ1ZjQ3ZmViNGQ3NWNiMzMzOTE0YmZkYjk5OWE0ODljOWQwZTMyMGQ1NDhmMzEwNDE5YWQ3MzhkMWUyNGI5In19fQ=="
    Displayname: "&6{MULTIPLIER}x {COLOR}Mnożnik monet"
    Lore:
    - ""
    - "&7Mnoży twoje monety"
    - "&7podczas grania na serwerze."
    - ""
    - "&8Odblokujesz to automatycznie"
    - "&8jeżeli zdobędziesz ten level."
    Locked-lore:
    - ""
    - "&cMusisz mieć {LEVEL} level aby to odblokować!"
    Unlocked-lore:
    - ""
    - "&aOdblokowane!"
    Veteran:
      Material: BEACON #Supports "CUSTOM_HEAD"
      #Supported in 1.14+ ONLY if you wanna use a custom resource pack
      Custom-model-data: 0
      #Only available if material is CUSTOM_HEAD
      Texture: "eyJ0ZXh0dXJlcyI6eyJTS0lOIjp7InVybCI6Imh0dHA6Ly90ZXh0dXJlcy5taW5lY3JhZnQubmV0L3RleHR1cmUvOTI2NWY5NmY1NGI3ODg4NWM0NmU3ZDJmODZiMWMxZGJmZTY0M2M2MDYwZmM3ZmNjOTgzNGMzZTNmZDU5NTEzNSJ9fX0="
      Displayname: "&6Nagrody najlepszych graczy"
      Lore:
      - "&7Nagrody dla najlepszych"
      - "&7graczy na serwerze!"
      Locked:
      - ""
      - "&cMusisz mieć level {LEVEL} lub"
      - "&cwiększy aby odblokować te nagrody!!"
      Unlocked:
      - ""
      - "&eKliknij aby otworzyć nagrody najlepszych graczy!"
      Slot: 44
  Previous:
    Material: ARROW #Supports "CUSTOM_HEAD"
    Custom-model-data: 0
    Texture: "eyJ0ZXh0dXJlcyI6eyJTS0lOIjp7InVybCI6Imh0dHA6Ly90ZXh0dXJlcy5taW5lY3JhZnQubmV0L3RleHR1cmUvYWQ3M2NmNjZkMzFiODNjZDhiODY0NGMxNTk1OGMxYjczYzhkOTczMjNiODAxMTcwYzFkODg2NGJiNmE4NDZkIn19fQ=="
    Displayname: "&aPoprzednia strona"
    Slot: 18
  Next:
    Material: ARROW #Supports "CUSTOM_HEAD"
    Custom-model-data: 0
    Texture: "eyJ0ZXh0dXJlcyI6eyJTS0lOIjp7InVybCI6Imh0dHA6Ly90ZXh0dXJlcy5taW5lY3JhZnQubmV0L3RleHR1cmUvYzg2MTg1YjFkNTE5YWRlNTg1ZjE4NGMzNGYzZjNlMjBiYjY0MWRlYjg3OWU4MTM3OGU0ZWFmMjA5Mjg3In19fQ=="
    Displayname: "&aNastępna strona"
    Slot: 26
  Back:
    Enabled: false
    Material: ARROW #SuLOLOLOLpports "CUSTOM_HEAD"
    Custom-model-data: 0
    Texture: "eyJ0ZXh0dXJlcyI6eyJTS0lOIjp7InVybCI6Imh0dHA6Ly90ZXh0dXJlcy5taW5lY3JhZnQubmV0L3RleHR1cmUvYmViNTg4YjIxYTZmOThhZDFmZjRlMDg1YzU1MmRjYjA1MGVmYzljYWI0MjdmNDYwNDhmMThmYzgwMzQ3NWY3In19fQ=="
    Displayname: "&cWyjście"
    #This command will be run BY THE PLAYER when back button is clicked. "none" to disable.
    #In case you need to use {PLAYER} to replace with player name or {UUID} with player uuid.
    Command: "none"
    Normal-slot: 50
    Veteran-slot: 50
  Extra:
    Enabled: false
    Material: ENCHANTED_BOOK #Supports "CUSTOM_HEAD"
    Custom-model-data: 0
    Texture: "eyJ0ZXh0dXJlcyI6eyJTS0lOIjp7InVybCI6Imh0dHA6Ly90ZXh0dXJlcy5taW5lY3JhZnQubmV0L3RleHR1cmUvN2RjOTg1YTdhNjhjNTc0ZjY4M2MwYjg1OTUyMWZlYjNmYzNkMmZmYTA1ZmEwOWRiMGJhZTQ0YjhhYzI5YjM4NSJ9fX0="
    Displayname: "&aQuests & Challenges"
    #Supports PlaceholderAPI is available
    Lore:
    - "&7Completing quests and challenges"
    - "&7will reward you with &6Coins&7, &3YourNetwork"
    - "&3Experience &7and more!"
    - ""
    - "&7You can complete a maximum of &a10"
    - "&7challenges every day."
    - ""
    - "&7Challenges completed today: &a%placeholder_quest%"
    - ""
    - "&eClick to view Quests & Challenges"
    #This command will be run BY THE PLAYER when Extra button is clicked (in slot 50). "none" to disable.
    #In case you need to use {PLAYER} to replace with player name or {UUID} with player uuid.
    Command: "none"
    Normal-slot: 50
    Veteran-slot: 50
  Main:
    Material: BREWING_STAND #Supports "CUSTOM_HEAD"
    Custom-model-data: 0
    Texture: "eyJ0ZXh0dXJlcyI6eyJTS0lOIjp7InVybCI6Imh0dHA6Ly90ZXh0dXJlcy5taW5lY3JhZnQubmV0L3RleHR1cmUvZGNlZGIyZjRjOTcwMTZjYWU3Yjg5ZTRjNmQ2OTc4ZDIyYWMzNDc2YzgxNWM1YTA5YTY3OTI0NTBkZDkxOGI2YyJ9fX0="
    Displayname: "&aTwój poziom"
    #Supports PlaceholderAPI is available.
    Lore:
    - "&7Grajac w gry i wykonująć questy"
    - "&7otrzymujesz &dDośwaidczenie"
    - ""
    - "&7Za każdy zdobyty poziom, mozesz"
    - "&7odebrać super &enagrody&7!"
    - ""
    - "        &fTwój poziom: &6%alonsolevels_level%"
    - "        &8[%alonsolevels_progress_bar%&8]"
    - ""
    - "&eKliknij aby odebrać nagrody!  "
    Normal-slot: 49
    Veteran-slot: 49
  #This item will be the replacement for "Veteran" item. if Options.Veteran-rewards is set to false.
  #If Veteran-rewards is true this will be IGNORED.
  Veteran-replacement:
    Enabled: true
    Material: CUSTOM_HEAD #Supports "CUSTOM_HEAD"
    Custom-model-data: 0
    Texture: "eyJ0ZXh0dXJlcyI6eyJTS0lOIjp7InVybCI6Imh0dHA6Ly90ZXh0dXJlcy5taW5lY3JhZnQubmV0L3RleHR1cmUvYzJkODQ3YjJjNzk4Njc4ZmQ1MmIwZTczNDhkY2Y5ZjUyMmY4NmE5Nzk4ZGE5YmIwM2NkZmJiYTI5MTFkZWM2NiJ9fX0="
    Displayname: "&bYou are awesome!"
    #Supports PlaceholderAPI is available.
    Lore:
    - "&7Thanks for playing with us %player_name%!"
    #Command to run when clicking the item. Set to "none" to disable.
    #Available placeholder are {PLAYER} and {UUID}
    Command: "none"

Options:
  #To apply changes for aliases you must RESTART the server.
  #Plugman or similar plugins are NOT and will NEVER be supported.
  #Use /reload or restart your server.
  Main-command: "bagietalevele"
  Aliases:
  Sub-commands:
    Rewards:
    - "nagrody"
    Stats:
    - "statystyki"
    Auto-claim:
    - "autoodbieranie"
    Reset:
    - "reset"
    Add-exp:
    - "dodajexp"
    Add-random-exp:
    - "dodajrandomowyexp"
    Remove-exp:
    - "usunexp"
    Set-exp:
    - "ustawexp"
    Add-level:
    - "dodajlevel"
    Remove-level:
    - "usunlevel"
    Set-level:
    - "ustawlevel"
    Reload:
    - "reload"
    Add-money:
    - "dodajmonety"
    Add-random-money:
    - "dodajrandomowemonety"
  Add-money:
    #If true, one decimal will be used to round.
    #If false, decimal format will be used.
    Decimal: true
  Colors:
    Enabled: true
  #What's the name of this server? Will be used to disable rewards if they are restricted to specific servers.
  Server: "Lobby"
  #Max level for players to level up. Recommended to leave it as 500.
  Max-level: 500
  #If enabled help message will include plugin name and version line.
  Support-developer: true
  Exp-formula:
    #If enabled "Expression" will be used. Make sure you KNOW WHAT YOU ARE DOING before modifying this.
    #Do not ask for support on how to make expressions. If you don't know how to, simply don't do it.
    Enabled: true
    #LEVEL will be replaced with the actual level.
    #Example: "(LEVEL-1) * 300" means that for:
    #Level 1 = exp required is always 0.
    #Level 2 = (2-1)*300 = 300 exp required
    #Level 3 = (3-1)*300 = 600 exp required
    #an so on..
    #WARNING: This formula is processed internally using eval methods.
    #That means that it can be used to modify everything internally if not used with caution.
    #That includes files, folders, etc. Make sure only YOU have access to this. You have been WARNED!
    #Recommended to leave this as default, it's based on the big network formula.
    Expression: "1250*(Math.pow(LEVEL,2))+ (6250*LEVEL) - 7500"
    #IMPORTANT:
    #The name explains everything. DO NOT ENABLE THIS UNLESS YOU KNOW WHAT YOU ARE DOING.
    #This will DELETE everything inside levels.yml and re generate it based on your exp formula, you can make modifications.
    #Make sure you DISABLE this after the file is generated, otherwise it will keep resetting your levels.yml file.
    #If your system doesn't support javascript expression, this will not work. Just use default levels.yml and disable this.
    Update-levels-file-based-on-formula: false
  #Required level to access veteran inventory (rewards - multipliers)
  Veteran-inventory: 100
  #Disable commands for normal users. (Players without admin permission)
  #Useful if you are using one server for each game like the big network.
  #If you are using multi-arena minigames or similar systems leave it as false and use "Disabled-worlds"
  Game-mode: false
  #Worlds in which normal users CAN perform commands related to this plugin so they cannot open
  #rewards gui or check statistics while playing in a map.
  #This doesn't affect players with admin permission.
  #Option useful to restrict the usage of commands for normal players in servers like Skywars or minigames.
  Enabled-worlds:
  - "lobby"
  - "main_lobby"
  - "world"
  #This will kick the player as soon as he joins if the data couldn't be loaded. (Or there was an error in database)
  Kick-on-fail:
    Enabled: true
    Reason:
    #Support PlaceholderAPI, it might not properly with many plugins because is most likely that
    #the placeholders are not loading at the moment the player is kicked. (because he just joined)
    #Available placeholders: {PLAYER} player name, {UUID} player uuid
    - "&cCouldn't load/register information."
    - "&fPlease reconnect to the server."
    - "&r"
    - "&7If problem persists contact an administrator."
  Normal-rewards:
    #TO ENABLE CUSTOMIZATION YOU MUST CHANGE THIS VALUE FROM 0 TO OTHER IN A RANGE OF 1 - 6 rows.
    Rows: 0
    Slots: "0,1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16,17,19,20,21,22,23,24,25"
  Veteran-rewards:
    #If false, item for veteran rewards will not be displayed.
    #This disables also Multipliers from veteran rewards.
    Enabled: true
    #TO ENABLE CUSTOMIZATION YOU MUST CHANGE THIS VALUE FROM 0 TO OTHER IN A RANGE OF 1 - 6 rows.
    Rows: 0
    #VETERAN REWARDS CAN ONLY BE 10 AT THE MOST. IT WONT USE PAGE SYSTEM.
    Slots: "10,11,12,13,14,15,16,19,20,21,22,23,24,25"
  Multipliers:
    #Set to false to disable normal multipliers.
    Normal: true
    Normal-slots: "36,37,38,39,40,41,42,43"
    #Set to false to disable veteran multipliers.
    #If true, they will work ONLY if "Veteran-rewards.Enabled" is true too.
    Veteran: true
    Veteran-slots: "38,39,40,41,42"
  Debug:
    #If true, some checks will be sent in console. If false, spam will not be sent.
    #Currently includes level/required experience spam when plugin starts.
    Enabled: false
  Leaderboards:
    #If enabled, leaderboards will be loaded.
    Enabled: true
    #Amount in minutes before first attempt to load data from database is made.
    First-delay: 2
    #Interval in minutes between plugin attempts to load information AND update leaderboards.
    #Recommended 10 minutes. Remember this is REQUIRED for Leaderboards.
    Interval: 10
  Auto-save:
    #Time in minutes to auto save player data. Minimum 0 (If zero it will be disabled). Recommended 7.
    #Remember this is REQUIRED for Leaderboards!!!
    Interval: 7
  Experience-bar:
    #Enable experience bar to display level progress?
    #This is made using packets. (ProtocolLib is REQUIRED)
    #This could cause issues with plugins that use player experience for anvils or similar systems.
    #USE IT ONLY IN LOBBY SERVERS.
    Enabled: false
    #Enabled worlds. Experience bar will be displayed in this worlds.
    #To enable it in all worlds set to => Worlds: []
    Worlds:
    - "world"
    - "lobby"
    #Time in TICKS between each update.
    Interval: 100
  Compatibility:
    #Recommended if you are using EssentialsChat. Some of my plugins add this support.
    #Make sure you enable ONLY if it's necessary. In addition, ONLY one is enough. If you have this option enabled in
    #one of my plugins you can disable this option in all others.
    #This allow you to use any placeholder from PlaceholderAPI but replacing it with brackets instead of percentage signs.
    #Example: %aplaceholder% => {aplaceholder}
    #This includes the ones that are not from AlonsoLevels.
    Chat: true
    #Should plugin attempt to fix HEX colors for 1.8 - 1.15 players?
    #THIS IS AN EXPERIMENTAL FEATURE AND MIGHT NOT WORK CORRECTLY.
    Hex-color-fix: true
  Auto-claim:
    #Set to true if you want to disable auto-claim feature in this server.
    #This will not affect player's auto-claim status when they switch servers.
    Restrict-server: false
  Items:
    #If enabled, items with custom durability will have also be unbreakable to allow custom textures in 1.9+
    Unbreakable-if-durability: true
  Money:
    Warning:
    - "Available types are VAULT,LEVEL, MATERIAL and PLAYER_POINTS."
    - "1) VAULT will attempt to hook with vault plugin."
    - "   If disabled, cost will take levels. YES, LEVELS, not experiences, LEVEL."
    - "   If enabled and Vault is available and hooked, cost will take money from balance, otherwise it will take LEVELS."
    - "   This is an experimental feature, please report bugs on discussion tab."
    - "2) LEVEL will use player level(experience)"
    - "3) PLAYER_POINTS will require PlayerPoints plugin to work. If plugin cannot be found, it will automatically use LEVEL."
    - "   This is IN BETA. Might not work correctly."
    - "4) TOKEN_MANAGER will require TokenManager plugin to work. If plugin cannot be found, it will automatically use LEVEL."
    - "   This is IN BETA. Might not work correctly."
    Type: PLAYER_POINTS
  #This is the amount of ticks the plugin will wait before loading data.
  #Useful if your have issues with players "losing" their stats on server change or reconnect.
  #Set to 0 to disable. If enabled, it's like that some plugins that send messages on join will not fetch correct data from placeholders.
  #To "fix" this use this plugin made by our team which adds messages on player join with an option to set delay.
  #We also support placeholder check to prevent message to be sent when player is in vanish mode. (Using placeholder to check if player is vanished)
  #Check our plugin on https://alonsoaliaga.com/AlonsoJoin (If available)
  Data-delay: 20

Permissions:
  Admin: "alonsolevels.admin"
  Stats-others: "alonsolevels.stats.others"
  Auto-claim: "alonsolevels.autoclaim"

Database:
  #Available types: MySQL and SQLite
  #You can use MySQL to make it global or you can use SQLite to make it local.
  #MySQL requires a server (local or external)
  #SQLite doesn't require anything, it's saved in a db file in the folder.
  Type: "SQLite"
  Table: "alonsolevels"
  #If type is SQLite
  File: "database-alonsolevels"
  #If type is MySQL
  Host: 127.0.0.1
  Port: 3306
  Database: "alonsolevels"
  Username: "root"
  Password: "12345"
  #Modify this just if you know what you are doing.
  #This will be added at the end of database url (Not in SQLITE, only in MySQL).
  #Useful if you want to set useSSL or autoReconnect or any other modifier.
  #This option is no longer used as HikariCP was implemented. Please use "HikariCP.Source-properties" options.
  Additional-url: ""
  #This option has been added to prevent connection timeout.
  #Time is in minutes. Every X minutes the plugin will run a test query to keep connection alive.
  #This option is no longer used as HikariCP was implemented.
  Keep-connection-interval: 30
  HikariCP:
    Warning:
    - "========================================================================================"
    - "You don't need to edit this text, it's ONLY displayed in config so you can read it."
    - "========================================================================================"
    - "HikariCP is experimental. Remember that only modify the following IF YOU KNOW HOW IT WORKS."
    - "You will not get support for HikariCP configurations as 1) I'm not a HikariCP advanced user"
    - "and 2) Customization depends on the owner and his knowledge level."
    - "Related to Source-properties, if you KNOW and want to add custom properties follow the format:"
    - "Source-properties:"
    - '  thePropertySelected1: "theValue1"'
    - '  thePropertySelected2: "theValue2"'
    - "[!] Remember to modify data only if you know what you are doing."
    - "Available source properties can be found here: https://alonsoaliaga.com/HikariCP-sp"
    - "Available source class names can be found here: https://alonsoaliaga.com/HikariCP-cn"
    Max-pool-size: 15
    #Set your custom source class name ONLY IF YOU KNOW WHAT IT IS.
    Custom-source-class-name: "default"
    #This is the source properties to modify your HikariCP configurations.
    #It allows you to select and specify custom configs IF YOU KNOW WHAT YOU ARE DOING.
    #Source properties can be found here: https://links.alonsoaliaga.com/HikariCP-sp
    Source-properties: []

Updates:
  #Auto update configuration? Enabling will delete comments.
  Auto-update-configuration: false
  #Check for updates? Recommended to keep it enabled.
  Check-updates: true
  #Notify updates when player with permission joins the server?
  Notify-updates: false
  #Permission required to receive update message.
  Permission: "alonsolevels.update"
  #Message to send when update is found.
  Message: "&6[AlonsoLevels] &eA new update has been found! You are using version {CURRENT}. Download version {NEW} here &c{LINK}"
