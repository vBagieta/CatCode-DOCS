# Spolszczenie [GadgetsMenu Premium](https://www.spigotmc.org/resources/gadgetsmenu-1-8-1-18-1-premium.62831/) przez [vBagieta](https://github.com/vBagieta)
### Spolszczenie nie jest gotowe w 100%!
**Poniżej jest pare spolszczeń!**

PLIK MESSAGES.YML
```
Prefix: ''
GUI-Menus:
  Main: Menu gadżetów
  Hats: Czapki
  Animated Hats: Animowane czapki
  Particles: Efekty
  Suits: Przebrania
  Gadgets: Gadżaty
  Pets: Zwierzaki
  Miniatures: Miniaturki
  Morphs: Przemiany
  Banners: Banery
  Emotes: Emotki
  Cloaks: Płaszcze
  Purchase-Menu:
    GUI-Name: Potwierdź płatność
    Items:
      Confirm:
        Name: '&aPotwierdź'
        Material: LIME_TERRACOTTA
        Slot: 11
        Lore: ''
      Cancel:
        Name: '&cAnuluj'
        Material: RED_TERRACOTTA
        Slot: 15
        Lore: ''
  Confirm-Open-Mystery-Box-Menu:
    GUI-Name: Potwierdź otworzenie boxa
    Items:
      Open:
        Name: '&aOtwórz'
        Material: GREEN_WOOL
        Slot: 29
        Lore:
        - '&7Otwórz tajemnicza skrzynie'
        - ''
        - '&7Tego nie da się cofnać!'
      Cancel:
        Name: '&cAnuluj'
        Material: RED_WOOL
        Slot: 33
        Lore:
        - '&7Cofniesz sie do'
        - '&7Menu tajemniczych skrzyń.'
  Mystery-Vault-Menu:
    GUI-Name: Tajemnicza skrzynia
    Items:
      Error:
        Name: '&cNIE!!!'
        Material: RED_STAINED_GLASS_PANE
        Slot: 22
        Lore:
        - '&cNie posiadasz żadnych Tajemniczych skrzyń!'
      Loading-Mystery-Boxes:
        Name: '&cŁadowanie...'
        Material: RED_STAINED_GLASS_PANE
        Slot: 22
        Lore:
        - '&7Ładowanie twoich skrzyń.'
        - '&7Otwórz ponownie menu Tajemniczych Skrzyń.'
      Craft-Mystery-Boxes:
        Name: '&eKup tajemnicza skrzynie!'
        Texture: http://textures.minecraft.net/texture/fe35d96a6d6786fbc1cd232c3556f8a857bdeb278bd662ee387a9a3b1174e4a7
        Show: true
        Slot: 49
        Lore:
        - '&7Posiadasz &e{MYSTERY_DUST}x &7monet.'
        Material: head:e52970e124153abd28b5d64003b8fd87999dbc7a5cde899961ee01ccd3d4ab98
      Gift-Inventory:
        Name: '&cPrezenty'
        Show: true
        Texture: http://textures.minecraft.net/texture/5e7981347b3cff63334002c914bf0420f4560c3abcd7e47bb2d0bbe3a92c25bb
        Slot: 48
        Lore:
        - '&7Wysylaj prezenty do swoich przyjaciol'
        - '&7i otrzymuj unikalne nagrody!'
        - ''
        - ''
        - '&7Prezenty Wyslane: &e{GIFT_SENT}'
        - '&7Prezenty Otrzymane: &e{GIFT_RECEIVED}'
        - ''
        - '&cNacisnij aby otworzyc menu prezentow!'
        Material: head:d2ac1c51807e261c12c4f2adbad36b8b2c497c277f7223ec244cb4608c59c
      Animations:
        Name: '&6Efekty'
        Material: head:48de339af63a229c9238d027e47f53eeb56141a419f51b35c31ea1494b435dd3
        Show: true
        Slot: 50
        Lore:
        - '&7Wybierz efekt twojej skrzyni.'
      Open-Multiple-Boxes:
        Name: '&eOtworz Wiele Boxow'
        Material: NETHER_STAR
        Show: false
        Slot: 51
        Lore:
        - '&eOtwiera kilka &6Tajemniczych skrzyń'
        - '&ew tym samym czasie!'
      Mystery-Box-Information:
        Name: '&aMystery Box Information'
        Material: BOOK
        Slot: 49
        Loot-Contain-Rarity: true
        Lore:
        - '&bMystery Boxes &7contains almost'
        - '&7any cosmetics items. To earn'
        - '&bMystery Boxes&7, all you have to'
        - '&7do is play on the server!'
        - ''
        - '&eYour 5 most recent items found are:'
        - '&71. {RECENT_LOOT_1}'
        - '&72. {RECENT_LOOT_2}'
        - '&73. {RECENT_LOOT_3}'
        - '&74. {RECENT_LOOT_4}'
        - '&75. {RECENT_LOOT_5}'
        - ''
        - '&7Your have: &b{MYSTERY_BOXES} Mystery Boxes'
  Mystery-Box-Crafting-Menu:
    GUI-Name: Kup tajemnicze skrzynie
    Items:
      1-Star:
        Name: '&6Tajemnicza skrzynia #1'
        Material: ENDER_CHEST
        Price: 100
        Lore:
        - '&7Ten Mystery Box zawiera:'
        - ''
        - '&aPospolite Przedmioty&7: &64'
        - '&9Rzadkie Przedmioty&7: &61'
        - '&5Epickie Przedmioty&7: &61'
        - '&6Legendarne Przedmioty&7: &61'
        - ''
        - '&7Jakosc: &e✰&7✰✰✰✰'
        Slot: 9
      2-Star:
        Name: '&6Tajemnicza skrzynia #2'
        Material: ENDER_CHEST
        Price: 200
        Lore:
        - '&7Ten Mystery Box zawiera:'
        - ''
        - '&aPospolite Przedmioty&7: &63'
        - '&9Rzadkie Przedmioty&7: &62'
        - '&5Epickie Przedmioty&7: &61'
        - '&6Legendarne Przedmioty&7: &61'
        - ''
        - '&7Jakosc: &e✰✰&7✰✰✰'
        Slot: 11
      3-Star:
        Name: '&6Tajemnicza skrzynia #3'
        Material: ENDER_CHEST
        Price: 300
        Lore:
        - '&7Ten Mystery Box zawiera:'
        - ''
        - '&aPospolite Przedmioty&7: &62'
        - '&9Rzadkie Przedmioty&7: &62'
        - '&5Epickie Przedmioty&7: &62'
        - '&6Legendarny Przedmioty&7: &61'
        - ''
        - '&7Jakosc: &e✰✰✰&7✰✰'
        Slot: 13
      4-Star:
        Name: '&6Tajemnicza skrzynia #4'
        Material: ENDER_CHEST
        Price: 400
        Lore:
        - '&7Ten Mystery Box zawiera:'
        - ''
        - '&aPospolite Przedmioty&7: &61'
        - '&9Rzadkie Przedmioty&7: &61'
        - '&5Epickie Przedmioty&7: &62'
        - '&6Legendarne Przedmioty&7: &63'
        - ''
        - '&7Jakosc: &e✰✰✰✰&7✰'
        Slot: 15
      5-Star:
        Name: '&6Tajemnicza skrzynia #5'
        Material: ENDER_CHEST
        Price: 550
        Lore:
        - '&7Ten Mystery Box zawiera:'
        - ''
        - '&aPospolite Przedmioty&7: &60'
        - '&9Rzadkie Przedmioty&7: &61'
        - '&5Epickie Przedmioty&7: &62'
        - '&6Legendarne Przedmioty&7: &64'
        - ''
        - '&7Jakosc: &e✰✰✰✰✰'
        Slot: 17
  Gift-Inventory-Menu:
    GUI-Name: Prezenty
    Items:
      Mystery-Gift:
        Name: '&6Tajemnicza paczka'
        Material: ENDER_CHEST
        Lore:
        - '&7Ta paczka zawiera'
        - '&65 Tajemniczych skrzyń&7.'
        - ''
        - '&eKliknij, aby wysłać prezent.'
      Error:
        Name: '&cO NIE!'
        Material: RED_STAINED_GLASS_PANE
        Slot: 22
        Lore:
        - '&7Nie masz żadnych Tajemniczych paczek!'
  Send-Gift-Menu:
    GUI-Name: Gracze online
    Items:
      Mystery-Gift:
        Name: '&6Tajemnicza paczka'
        Material: ENDER_CHEST
        slot: 4
        Lore:
        - '&7Ta paczka zawiera'
        - '&65 Tajemniczych skrzyń&7.'
        - ''
        - '&eKliknij, aby wysłać prezent.'
        Slot: 4
      Player:
        Lore:
        - ''
        - '&aClick to send the gift!'
  Confirm-Send-Gift-Menu:
    GUI-Name: Potwierdź wysłanie prezentu
    Items:
      Player:
        Name: '&7{PLAYER}'
        Slot: 12
        Lore: ''
      Mystery-Gift:
        Name: '&6Tajemnicza paczka'
        Material: ENDER_CHEST
        Slot: 14
        Lore:
        - '&7Ta paczka zawiera'
        - '&65 Tajemniczych skrzyń&7.'
      Confirm:
        Name: '&aPotwierdź'
        Material: LIME_TERRACOTTA
        Slot: 29
        Lore: ''
      Cancel:
        Name: '&cAnuluj'
        Material: RED_TERRACOTTA
        Slot: 33
        Lore: ''
  Mystery-Vault-Animations-Menu:
    GUI-Name: Efekty otwierania skrzyń
    Items:
      Random-Mystery-Vault-Animation:
        Name: '&6Losowy efekt'
        Material: head:48de339af63a229c9238d027e47f53eeb56141a419f51b35c31ea1494b435dd3
        Show: true
        Slot: 41
        Lore:
        - '&7Nie umiesz wybrać'
        - '&7animacji skrzyni?'
        - '&7Już nie musisz się martwić!'
        - ''
        - '&eStatus: &a{STATUS}'
  Open-Multiple-Boxes-Menu:
    GUI-Name: Open Multiple Boxes
    Items:
      Open-20-Boxes:
        Name: '&aOpen 20 Boxes'
        Material: NETHER_STAR
        Slot: 19
        Lore:
        - '&7Open up to 20 boxes at the'
        - '&7same time.'
      Open-50-Boxes:
        Name: '&aOpen 50 Boxes'
        Material: NETHER_STAR
        Slot: 22
        Lore:
        - '&7Open up to 50 boxes at the'
        - '&7same time.'
      Open-250-Boxes:
        Name: '&aOpen 250 Boxes'
        Material: NETHER_STAR
        Slot: 25
        Lore:
        - '&7Open up to 250 boxes at the'
        - '&7same time.'
  Confirm-Open-Multiple-Boxes-Menu:
    GUI-Name: Confirm Open Multiple Boxes
    Items:
      Confirm:
        Name: '&aConfirm'
        Material: LIME_TERRACOTTA
        Slot: 11
        Lore: ''
      Cancel:
        Name: '&cCancel'
        Material: RED_TERRACOTTA
        Slot: 15
        Lore: ''
  Pet-Items-Menu:
    GUI-Name: Pet Consumables
    Items:
      Your-Pet:
        Name: '&eTwój zwierzak'
        Show: true
        Slot: 50
      Zero-Item-Remain:
        Show-Custom-Item: true
        Material: GRAY_DYE
        Play-Sound:
          Enabled: true
          Sound: ENTITY_ENDERMAN_TELEPORT
  Settings-Menu:
    GUI-Name: Settings
    Items:
      Ignore-Cooldown:
        Name: '&aIgnore Cooldown'
        Material: BARRIER
        Show: true
        Slot: 20
        Lore: ''
      Self-Morph-View:
        Name: '&aSelf Morph View'
        Material: ENDER_EYE
        Show: true
        Slot: 24
        Lore: ''
      Enabled:
        Name: '&aEnabled'
        Material: LIME_WOOL
        Lore: ''
      Disabled:
        Name: '&cDisabled'
        Material: RED_WOOL
        Lore: ''
Items:
  Go-Back:
    Name: '&ePowrót'
    Material: head:816ea34a6a6ec5c051e6932f1c471b7012b298d38d179f1b487c413f51959cd4
    Show: true
    Slot: 39
    Lore: ''
  Previous-Page:
    Name: '&aPoprzednia strona'
    Material: head:8652e2b936ca8026bd28651d7c9f2819d2e923697734d18dfdb13550f8fdad5f
    Slot: 39
    Lore:
    - '&eStrona {PAGE}'
  Next-Page:
    Name: '&aNastepna strona'
    Material: head:2a3b8f681daad8bf436cae8da3fe8131f62a162ab81af639c3e0644aa6abac2f
    Slot: 41
    Lore:
    - '&eStrona {PAGE}'
  Already-Selected:
    Show-In-Lore: true
    Lore:
    - ''
    - '&6Aktywne'
  Click-To-Select:
    Show-In-Lore: true
    Lore:
    - ''
    - '&eKliknij by wybrać'
  Unlocked:
    Show-In-Lore: true
    Lore:
    - ''
    - '&7Odblokowano: &c{HASPERMISSION}/{SIZE} &8({PERCENTAGE}%)'
    - ''
    - '&eNacisnij Aby Przegladac!'
  MainMenu-Item:
    Name: '&6Glowne Menu'
    Material: head:c2ed298858951b43d2448db5c656e7004eb91e3076e5fc88d24e529e8849e2c0
    Show: true
    Lore:
    - '&7Monety: &e{MYSTERY_DUST}x'
    - '&7Tajemniczych skrzynie: &6x{MYSTERY_BOXES}'
    Slot: 48
  Morph-Slimeball:
    Name: '&6Aktywuj umiejetnosc przemiany'
  Self-Morph-View:
    Name: '&eWidzenie wlasnej przemiany'
    Material: head:6f89b150be9c4c5249f355f68ea0c4391300a9be1f260d750fc35a1817ad796e
    Show: true
    Lore:
    - '&7Status: {STATUS}'
    - ''
    - '&eNacisnij aby przelaczyc tryb widzenia przemiany'
    Slot: 50
  Rename-Pet:
    Name: '&eNazwij swojego zwierzaka'
    Material: NAME_TAG
    Show: true
    Lore:
    - '&7Zmien nazwe swojego zwierzaka poprzez napisanie jej na czacie.'
    Slot: 53
  Send-Pet-On-Mission:
    Name: '&aSend Pets on a Mission'
    Material: OAK_BOAT
    Show: false
    Slot: 45
    Lore:
    - '&7Sends all your &2Happy, &aVery'
    - '&aHappy&7, and &6Super Happy &7pets'
    - '&7on a top-secret pet mission'
    - '&7in order to gain Pet EXP!'
    - ''
    - '&7The amount of Pet EXP gained'
    - '&7is increased the happier'
    - '&7your pet is.'
  Pages:
    Name: ' &r(Strona {CURRENT_PAGE}/{MAX_PAGES})'
  Enough-Mystery-Dust:
    Lore:
    - ''
    - '&7Nacisnij aby kupić za &e{COST}x &7monet!'
    Play-Sound:
      Enabled: true
      Sound: ENTITY_EXPERIENCE_ORB_PICKUP
  Not-Enough-Mystery-Dust:
    Lore:
    - ''
    - '&7Nacisnij aby kupić za &e{COST}x &7monet!'
    Play-Sound:
      Enabled: true
      Sound: ENTITY_ENDERMAN_TELEPORT
  Enough-Mystery-Dust-To-Craft-Mystery-Box:
    Lore:
    - ''
    - '&7Koszt &e{COST}x &7monet!'
    - '&eNacisnij aby stworzyc!'
    Play-Sound:
      Enabled: true
      Sound: ENTITY_EXPERIENCE_ORB_PICKUP
  Not-Enough-Mystery-Dust-To-Craft-Mystery-Box:
    Lore:
    - ''
    - '&7Nacisnij aby stworzyc za &e{COST}x &7monet!'
    - '&cMusisz miec {COST}x &emonet&c wiecej!'
    Play-Sound:
      Enabled: true
      Sound: ENTITY_ENDERMAN_TELEPORT
  Item-Unpurchasable:
    Lore:
    - ''
    - '&cNie możesz tego kupić!.'
    Play-Sound:
      Enabled: true
      Sound: ENTITY_ENDERMAN_TELEPORT
  Failed-To-Purchase:
    Play-Sound:
      Enabled: true
      Sound: ENTITY_ENDERMAN_TELEPORT
  Failed-To-Deduct-Mystery-Dust:
    Play-Sound:
      Enabled: true
      Sound: ENTITY_ENDERMAN_TELEPORT
  Multiple-Boxes-Loot-Book:
  - '       &1&lMYSTERY BOX'
  - ''
  - '&0Znalazles'
  - '&0nastepujacy lup w swoich'
  - '&0Mystery Boxach:'
  - '&9&l+{MYSTERY_DUST}x &dGrzybków'
  - ''
  - '&9&l{MYSTERY_BOXES_OPENED}x &0Mystery Boxe otworzony'
  - ''
  - ''
  - '&0Przejdz do nastepnej strony'
  - '&0aby zobaczyc wszystkie przedmioty'
  Settings-Status:
  - '&e&l{SETTING}'
  - ''
  - '  &eStatus: &6{STATUS}'
  - ''
  Current-Spawned-Pet:
    Name: '&eObecny zwierzak'
    Show: true
    Slot: 41
  Equip-Entire-Suit:
    Name: '&eZałóż na siebie cały strój'
    Material: LEATHER
    Show: true
    Slot: 41
    Lore:
    - '&eZałóż wszytkie częsci stroju'
    - '&ejeżeli tylko masz je odblokowane!'
  Settings:
    Name: '&eSettings'
    Material: COMPARATOR
    Show: false
    Slot: 53
    Lore:
    - '&7Allow you to edit and control'
    - '&7various personal settings.'
Reset-Buttons:
  Reset-Cosmetics:
    Name: '&cResetuj kosmetyki'
    Material: head:b1f868761a5c9139da1fec6726e1655929429a43ab972c8118ba26b9255e7c
    Show: true
    Slot: 50
    Lore: ''
    Play-Sound:
      Enabled: true
      Sound: ENTITY_EXPERIENCE_ORB_PICKUP
  Reset-Hat:
    Name: '&cResetuj czapki'
    Material: head:b1f868761a5c9139da1fec6726e1655929429a43ab972c8118ba26b9255e7c
    Show: true
    Slot: 40
    Lore: ''
    Play-Sound:
      Enabled: true
      Sound: ENTITY_EXPERIENCE_ORB_PICKUP
  Reset-Animated-Hat:
    Name: '&cResetuj animowane czapki'
    Material: head:b1f868761a5c9139da1fec6726e1655929429a43ab972c8118ba26b9255e7c
    Show: true
    Slot: 40
    Lore: ''
    Play-Sound:
      Enabled: true
      Sound: ENTITY_EXPERIENCE_ORB_PICKUP
  Reset-Particle:
    Name: '&cResetuj efekty'
    Material: head:b1f868761a5c9139da1fec6726e1655929429a43ab972c8118ba26b9255e7c
    Show: true
    Slot: 40
    Lore: ''
    Play-Sound:
      Enabled: true
      Sound: ENTITY_EXPERIENCE_ORB_PICKUP
  Reset-Suit:
    Name: '&cResetuj przebrania'
    Material: head:b1f868761a5c9139da1fec6726e1655929429a43ab972c8118ba26b9255e7c
    Show: true
    Slot: 40
    Lore: ''
    Play-Sound:
      Enabled: true
      Sound: ENTITY_EXPERIENCE_ORB_PICKUP
  Reset-Gadget:
    Name: '&cResetuj gadżety'
    Material: head:b1f868761a5c9139da1fec6726e1655929429a43ab972c8118ba26b9255e7c
    Show: true
    Slot: 40
    Lore: ''
    Play-Sound:
      Enabled: true
      Sound: ENTITY_EXPERIENCE_ORB_PICKUP
  Reset-Pet:
    Name: '&cResetuj zwierzaki'
    Material: head:b1f868761a5c9139da1fec6726e1655929429a43ab972c8118ba26b9255e7c
    Show: true
    Slot: 40
    Lore: ''
    Play-Sound:
      Enabled: true
      Sound: ENTITY_EXPERIENCE_ORB_PICKUP
  Reset-Miniature:
    Name: '&cResetuj miniatórki'
    Material: head:b1f868761a5c9139da1fec6726e1655929429a43ab972c8118ba26b9255e7c
    Show: true
    Slot: 40
    Lore: ''
    Play-Sound:
      Enabled: true
      Sound: ENTITY_EXPERIENCE_ORB_PICKUP
  Reset-Morph:
    Name: '&cResetuj przemiany'
    Material: head:b1f868761a5c9139da1fec6726e1655929429a43ab972c8118ba26b9255e7c
    Show: true
    Slot: 40
    Lore: ''
    Play-Sound:
      Enabled: true
      Sound: ENTITY_EXPERIENCE_ORB_PICKUP
  Reset-Banner:
    Name: '&cResetuj banery'
    Material: head:b1f868761a5c9139da1fec6726e1655929429a43ab972c8118ba26b9255e7c
    Show: true
    Slot: 40
    Lore: ''
    Play-Sound:
      Enabled: true
      Sound: ENTITY_EXPERIENCE_ORB_PICKUP
  Reset-Emote:
    Name: '&cResetuj emotki'
    Material: head:b1f868761a5c9139da1fec6726e1655929429a43ab972c8118ba26b9255e7c
    Show: true
    Slot: 40
    Lore: ''
    Play-Sound:
      Enabled: true
      Sound: ENTITY_EXPERIENCE_ORB_PICKUP
  Reset-Cloak:
    Name: '&cResetuj płaszcze'
    Material: head:b1f868761a5c9139da1fec6726e1655929429a43ab972c8118ba26b9255e7c
    Show: true
    Slot: 40
    Lore: ''
    Play-Sound:
      Enabled: true
      Sound: ENTITY_EXPERIENCE_ORB_PICKUP
Cooldown-In-Action-Bar:
  Enabled: true
  Cooldown-Block:
    Remain: '&7❚'
    Retain: '&a❚'
    Amount-Of-Blocks: 30
  Cooldown-Message: '&f{COOLDOWN_BLOCK}'
Item-Purchase-Messages:
  Purchase-Hat: '{PREFIX}&eZakupiles {ITEM}&e.'
  Purchase-Animated-Hat: '{PREFIX}&eZakupiles {ITEM}&e.'
  Purchase-Particle: '{PREFIX}&eZakupiles {ITEM}&e.'
  Purchase-Suit: '{PREFIX}&eZakupiles {ITEM}&e.'
  Purchase-Gadget: '{PREFIX}&eZakupiles {ITEM}&e.'
  Purchase-Pet: '{PREFIX}&eZakupiles {ITEM}&e.'
  Purchase-Morph: '{PREFIX}&eZakupiles {ITEM}&e.'
  Purchase-Banner: '{PREFIX}&eZakupiles {ITEM}&e.'
  Purchase-Emote: '{PREFIX}&eZakupiles {ITEM}&e.'
  Purchase-Cloak: '{PREFIX}&eZakupiles {ITEM}&e.'
  Purchase-Miniature: '{PREFIX}&eYou purchased {ITEM}&e.'
Checking-For-Update: '{PREFIX}&rChecking for updates...'
Cooldown: '{PREFIX}&cPoczekaj jeszcze {COOLDOWN}s &czanim tego uzyjesz!'
Error: '{PREFIX}&cWystapil blad podczas przetwarzania tej operacji!'
No-Permission: '{PREFIX}&cNie posiadasz wymaganej permisji!'
World-Disabled: '{PREFIX}&cNie posiadasz permisji aby zrobic to w tym swiecie!'
Banners-Are-Disabled: '{PREFIX}&cBanery sa wylaczone!'
Cloaks-Are-Disabled: '{PREFIX}&cPeleryny sa wylaczone!'
Emotes-Are-Disabled: '{PREFIX}&cEmotki sa wylaczone!'
Gadgets-Are-Disabled: '{PREFIX}&cGadzety sa wylaczone!'
Hats-Are-Disabled: '{PREFIX}&cCzapki sa wylaczone!'
Animated-Hats-Are-Disabled: '{PREFIX}&cAnimowane Czapki sa wylaczone!'
Morphs-Are-Disabled: '{PREFIX}&cMorfy sa wylaczone!'
Particles-Are-Disabled: '{PREFIX}&cPartkile sa wylaczone!'
Pets-Are-Disabled: '{PREFIX}&cZwierzatka sa wylaczone!'
Suits-Are-Disabled: '{PREFIX}&cStroje sa wylaczone!'
Equip-Animated-Hat-For-Player: '&eWybrales {ANIMATED_HAT} dla &6{PLAYER}&e.'
Equip-Banner-For-Player: '&eWybrales {BANNER} dla &6{PLAYER}&e.'
Equip-Cloak-For-Player: '&eWybrales {CLOAK} dla &6{PLAYER}&e.'
Equip-Emote-For-Player: '&eWybrales {EMOTE} dla &6{PLAYER}&e.'
Equip-Gadget-For-Player: '&eWybrales {GADGET} dla &6{PLAYER}&e.'
Equip-Hat-For-Player: '&eWybrales {HAT} dla &6{PLAYER}&e.'
Equip-Morph-For-Player: '&eUstawiles morf &6{PLAYER} &ena {MORPH}&e.'
Equip-Particle-For-Player: '&eWybrales {PARTICLE} dla &6{PLAYER}&e.'
Equip-Pet-For-Player: '&eUstawiles zwierzatko {PET} &edla &6{PLAYER}.'
Equip-Suit-For-Player: '&eWybrales {SUIT} dla &6{PLAYER}&e.'
Select-Animated-Hat: '&aYou selected &e{ANIMATED_HAT}&a.'
Select-Banner: '&eWybrałeś &6{BANNER}&e.'
Select-Cloak: '&eWybrałeś &6{CLOAK}&e.'
Select-Emote: '&eWybrałeś &6{EMOTE}&e.'
Select-Gadget: '&eWybrałeś &6{GADGET}&e.'
Select-Hat: '&eWybrałeś &6{HAT}&e.'
Select-Miniature: '&eWybrałeś &6{MINIATURE}&e.'
Select-Morph: '&eZamieniłeś się w {MORPH}&e.'
Select-Particle: '&eWybrałeś &6{PARTICLE}&e.'
Select-Pet: '&eZespawniłeś &e{PET} &ezwierzaka.'
Select-Suit: '&eWybrałeś &6{SUIT}&a.'
Select-Entire-Suit: '&eUbrałeś &6{PIECES} &ecześć stroju &6{SUIT}&e.'
No-Suit-Pieces-To-Equip: '&cNie masz żadnych części stroju do założenia!'
Reset-Animated-Hat: '&eZresetuj swoja animowana czapke.'
Reset-Banner: '&eZresetowano twoj baner.'
Reset-Cloak: '&eZresetowano swoja peleryne.'
Reset-Cosmetics: '&eZresetowano aktywne kosmetyki.'
Reset-Emote: '&eZresetowano swoja emotke.'
Reset-Gadget: '&eZresetowano swoj gadzet.'
Reset-Hat: '&eZresetowano swoja czapke.'
Reset-Morph: '&eZresetowano swoj morf.'
Reset-Particle: '&eZresetowano swoje parkitle.'
Reset-Pet: '&eZresetowano swoje zwierzatko.'
Reset-Suit: '&eZresetowano swoj stroj.'
Reset-Suit-Helmet: '&eZresetowano swoj helm.'
Reset-Suit-Chestplate: '&eZresetowano swoj napiersnik.'
Reset-Suit-Leggings: '&eZresetowano swoje spodnie.'
Reset-Suit-Boots: '&eZresetowano swoje buty.'
Reser-Miniature: '&eZresetowano swoja figurke'
Granted-Access-To-Animated-Hat: '&eYou''ve been granted permission to equip {ANIMATED_HAT}&e.'
Granted-Access-To-Banner: '&eYou''ve been granted permission to equip {BANNER}&e.'
Granted-Access-To-Cloak: '&eYou''ve been granted permission to equip {CLOAK}&e.'
Granted-Access-To-Emote: '&eYou''ve been granted permission to equip {EMOTE}&e.'
Granted-Access-To-Gadget: '&eYou''ve been granted permission to equip {GADGET}&e.'
Granted-Access-To-Hat: '&eYou''ve been granted permission to equip {HAT}&e.'
Granted-Access-To-Miniature: '&eYou''ve been granted permission to equip {MINIATURE}&e.'
Granted-Access-To-Morph: '&eYou''ve been granted permission to equip {MORPH}&e.'
Granted-Access-To-Particle: '&eYou''ve been granted permission to equip {PARTICLE}&e.'
Granted-Access-To-Pet: '&eYou''ve been granted permission to equip {PET}&e.'
Granted-Access-To-Suit: '&eYou''ve been granted permission to equip {SUIT}&e.'
Granted-Access-To-Animated-Hat-For-Player: '&e{PLAYER} is now allowed to use {ANIMATED_HAT}&e.'
Granted-Access-To-Banner-For-Player: '&e{PLAYER} is now allowed to use {BANNER}&e.'
Granted-Access-To-Cloak-For-Player: '&e{PLAYER} is now allowed to use {CLOAK}&e.'
Granted-Access-To-Emote-For-Player: '&e{PLAYER} is now allowed to use {EMOTE}&e.'
Granted-Access-To-Gadget-For-Player: '&e{PLAYER} is now allowed to use {GADGET}&e.'
Granted-Access-To-Hat-For-Player: '&e{PLAYER} is now allowed to use {HAT}&e.'
Granted-Access-To-Miniature-For-Player: '&e{PLAYER} is now allowed to use {MINIATURE}&e.'
Granted-Access-To-Morph-For-Player: '&e{PLAYER} is now allowed to use {MORPH}&e.'
Granted-Access-To-Particle-For-Player: '&e{PLAYER} is now allowed to use {PARTICLE}&e.'
Granted-Access-To-Pet-For-Player: '&e{PLAYER} is now allowed to use {PET}&e.'
Granted-Access-To-Suit-For-Player: '&e{PLAYER} is now allowed to use {SUIT}&e.'
No-Longer-Have-Access-To-Animated-Hat: '&eYou no longer have access to {ANIMATED_HAT}&e.'
No-Longer-Have-Access-To-Banner: '&eYou no longer have access to {BANNER}&e.'
No-Longer-Have-Access-To-Cloak: '&eYou no longer have access to {CLOAK}&e.'
No-Longer-Have-Access-To-Emote: '&eYou no longer have access to {EMOTE}&e.'
No-Longer-Have-Access-To-Gadget: '&eYou no longer have access to {GADGET}&e.'
No-Longer-Have-Access-To-Hat: '&eYou no longer have access to {HAT}&e.'
No-Longer-Have-Access-To-Miniature: '&eYou no longer have access to {MINIATURE}&e.'
No-Longer-Have-Access-To-Morph: '&eYou no longer have access to {MORPH}&e.'
No-Longer-Have-Access-To-Particle: '&eYou no longer have access to {PARTICLE}&e.'
No-Longer-Have-Access-To-Pet: '&eYou no longer have access to {PET}&e.'
No-Longer-Have-Access-To-Suit: '&eYou no longer have access to {SUIT}&e.'
Characters-Too-Long: '{PREFIX}&cImie zwierzaka nie moze byc dluzsze niz {CHARACTERS}
  znakow!'
Does-Not-Support-Characters: '{PREFIX}&cMozesz uzyc tylko angielskiego alfebetu w
  nazwie.'
Does-Not-Support-Special-Characters: '{PREFIX}&cNie mozesz uzyc specjalnych znakow
  w nazwie.'
No-Player-Nearby: '{PREFIX}&cBrak graczy niedaleko!'
Not-Allowed-From-Console: '{PREFIX}&cNie mozesz uzyc tej komendy z konsoli!'
Not-Allow-Teleport-To-That-Location: '{PREFIX}&cNie mozesz teleportowac sie do tej
  lokacji'
Not-Allow-Cosmetics-In-This-Location: '{PREFIX}&cNie mozesz uzywac kosmetykow w tej
  lokacji'
Not-Enough-Space: '{PREFIX}&cZa malo miejsca wokol Ciebie, aby uzyc tego gadzetu!'
Not-Enough-Space-For-Target-Block: '{PREFIX}&cZa malo miejsca na bloku, ktory wybrales
  aby uzyc tego gadzetu!'
Not-On-Ground: '{PREFIX}&cMusisz stac na ziemi aby tego uzyc!'
Not-On-Flat-Ground: '{PREFIX}&cMusisz stac na plaskiej ziemi aby tego uzyc!'
Stand-On-Two-Blocks-High: '{PREFIX}&cMusisz stac na wyzej niz 2 bloki wysokosci solidnych
  blokow!'
Player-Not-Found: '{PREFIX}&cGracz nie znaleziony!'
Player-Is-Offline: '{PREFIX}&cGracz jest offline!'
Plugin-Reloaded: '{PREFIX}&3Plugin GadgetsMenu zostal przeladowany.'
Reloading-Plugin: '{PREFIX}&3Przeladowywanie pluginu...'
Required-Number-Format: '{PREFIX}&cNumer jest wymagany!'
Required-Positive-Number: '{PREFIX}&cPozytywny numer jest wymagany!'
Target-A-Block: '{PREFIX}&cMusisz celowac na blok!'
Target-A-Player: '{PREFIX}&cMusisz celowac na gracza!'
Remove-Item-From-Slot-To-Equip-Gadget: '{PREFIX}&cMusisz usunac item w slocie {SLOT}(&6{ITEM}&c)
  aby wybrac gadzet!'
Remove-Item-From-Slot-To-Equip-Morph: '{PREFIX}&cMusisz usunac item w slocie {SLOT}(&6{ITEM}&c)
  aby wybrac morf!'
Remove-Item-From-Slot-To-Equip-Emote: '{PREFIX}&cMusisz usunac item w slocie {SLOT}(&6{ITEM}&c)
  aby wybrac emotke!'
Remove-Helmet-To-Equip-Hat: '{PREFIX}&cMusisz usunac swoj helm zalozyc czapke!'
Remove-Helmet-To-Equip-Animated-Hat: '{PREFIX}&cMusisz usunac swoj helm aby zalozyc
  animowana czapke'
Remove-Helmet-To-Equip-Banner: '{PREFIX}&cMusisz usunac swoj helm aby zalozyc baner!'
Remove-Helmet-To-Equip-Emote: '{PREFIX}&cMusisz usunac swoj helm aby zalozyc emotke!'
Remove-Armor-To-Equip-Suit: '{PREFIX}&cMusisz usunac swoja zbroje aby zalozyc stroj!'
Failed-To-Purchase: '&cWystapil blad przy kupowaniu przedmiotu!'
Item-Unpurchasable: '{PREFIX}&cNie mozesz kupic tego przedmiotu!'
Player-Not-Enough-MysteryDust: '{PREFIX}&cMozesz miec tylko &6{MYSTERY_DUST}x &cMonet!'
Added-MysteryDust: '{PREFIX}&eDodales &6{MYSTERY_DUST}x &eMystery Dust graczu &6{PLAYER}&e.'
Added-MysteryDust-To-All-Players: '{PREFIX}&eDodales &6{MYSTERY_DUST}x &eMonet dla
  graczy &6{ONLINE}&e.'
Check-MysteryDust: '&e{PLAYER} posiada &6{MYSTERY_DUST}x &eMonet.'
Received-MysteryDust: '{PREFIX}&eOtrzymales &6{MYSTERY_DUST}x &eMonet.'
Removed-MysteryDust: '{PREFIX}&eUsunales &6{MYSTERY_DUST}x &eMonet Dust graczowi &6{PLAYER}&e.'
Sent-MysteryDust: '{PREFIX}&eWyslales &6{MYSTERY_DUST}x &eMonet do &6{PLAYER}&e.'
Set-MysteryDust: '{PREFIX}&eUstawiles Monety gracza &6{PLAYER} na &6{MYSTERY_DUST}&e.'
Only-Have-MysteryDust: '{PREFIX}&6{PLAYER} &cposiada tylko &6{MYSTERY_DUST}x &cMonett!'
Removed-MysteryDust-From-Player: '{PREFIX}&6{MYSTERY_DUST}x 0&eMonet zostalo usuniete
  z twojego konta.'
Set-Player-MysteryDust: '{PREFIX}&eTwoje moenty zostal ustawiony na &6{MYSTERY_DUST}&e.'
Not-Enough-MysteryDust-To-Purchase: '&cNie masz wystarczająco Monet!'
Pay-MysteryDust-To-Self: '{PREFIX}&cNie mozesz zaplacicMonet samemu sobie!'
Gave-Mystery-Boxes: '{PREFIX}&eDales &6{MYSTERY_BOXES}x Skrzyń &egraczu &6{PLAYER}&e.'
Gave-Mystery-Boxes-To-All-Players: '{PREFIX}&eDales &6{MYSTERY_BOXES}x Skrzyń &etdla
  graczy &6{ONLINE}&e.'
Received-Mystery-Boxes: '{PREFIX}&eOtrzymales &6{MYSTERY_BOXES}x Skrzyń &eod &6{PLAYER}&e.'
Added-Mystery-Vault: '{PREFIX}&aKupiono Tajemnicza skrzynia &f''{NAME}''&a.'
Redefined-Mystery-Vault: '{PREFIX}&aLokacja Tajemnicza skrzynia &f''{NAME}'' &azostala
  na nowo zdefiniowana.'
Mystery-Vault-Same-Location: '{PREFIX}&cJuz stworzyles Tajemnicza skrzynia w tym miejscu!'
Mystery-Vault-Is-Exists: '{PREFIX}&cTajemnicza skrzynia o tej nazwie juz istnieje!'
Do-Not-Have-Any-Mystery-Vault: '{PREFIX}&cNie posiadasz tajemniczych skrzyń!'
No-Mystery-Vault-Nearby: '{PREFIX}&cBrak Tajemnicza skrzyniaow w podanym promieniu!'
Removed-Mystery-Vault: '{PREFIX}&aUsunieto Tajemnicza skrzynia &f''{NAME}''&a.'
Mystery-Vault-Not-Found: '{PREFIX}&cNie znaleziono zadnego Tajemnicza skrzynia w tym
  miejscu!'
Mystery-Vault-Not-Found-With-Name: '{PREFIX}&cNie znaleziono zadnego Tajemnicza skrzynia
  &f''{NAME}''&c!'
Teleport-To-Mystery-Vault: '{PREFIX}&eZostales przeteleportowany do Tajemniczej skrzyni'
Open-Mystery-Vault-At-A-Time: '{PREFIX}&cPoczekaj jak pierwszy gracz kupi skrzynie!'
Can-Only-Open-One-Mystery-Box: '{PREFIX}&cPoczekaj az pierwsza Tajmenicza skrzynia
  zostanie otwarta!'
Purchase-Cancelled: '{PREFIX}&cZakup Anulowany!'
Mystery-Boxes-Are-Disabled: '{PREFIX}&cMystery Boxy sa wylaczone!'
Crafted-Mystery-Box: '&eKupiłeś &6{NAME}&e.'
Gave-Mystery-Gifts: '{PREFIX}&eDarowales &6{GIFTS} &ePrezent/ow dla &r{PLAYER}&e.'
Received-Mystery-Gifts: '{PREFIX}&eOtrzymales &6{GIFTS} &ePrezent/ow od &r{PLAYER}&e.'
Send-A-Gift-To-Player: '&aWyslales prezent zawierajacy &65x Tajemniczych skrzyń &ado
  &r{PLAYER}&a!'
Received-Gift: '&aOtrzymales Prezent od &r{PLAYER}&a! Odwiedz &6Tajemnicza skrzynia&a,
  zeby go otworzyc!'
Mystery-Box-Was-Expired: '{PREFIX}&cTa Tajemnicza skrzynia jest przedawniony. Prosze
  otworz swoj Mystery Box zanim sie przedawni.'
Check-Mystery-Boxes: '&e{PLAYER} posiada &6{MYSTERY_BOXES}x &eTajemniczycn skrzyń'
Select-Mystery-Vault-Animation: '&7Wybrales &a{ANIMATION} &7dla swojej Tajmeniczej
  skrzyni'
Not-Enough-Mystery-Boxes: '&cNie posiadasz wystarczajaco duzo Tajemniczych skrzyń.'
Counting-Mystery-Boxes: '&cLiczenie Mystery Boxow...'
Emote-Is-Activated: '{PREFIX}&cEmotka jest juz aktywna!'
Gadget-Is-Activated: '{PREFIX}&cGadzet {GADGET} jest juz aktywny!'
Morph-Skill-Is-Activated: '{PREFIX}&cUmiejetnosc {MORPH} jest juz aktywna!'
Suit-Ability-Is-Activated: '{PREFIX}&cStroj {SUIT} jest juz aktywny!'
Is-Not-Morphed: '&cNie posiadasz zadnego morfa!'
Morph-Ability-Is-Disabled: '{PREFIX}&cUmiejetnosc {MORPH} jest obecnie wylaczona!'
Rename-Pet: '&eUstawiono nazwe twojego zwierzaka na &a{NAME}&e.'
Rename-Pet-For-Player: '&eUstawiono imie zwierzaka gracza {PLAYER} na &a{NAME}&e.'
Rename-Pet-In-Chat: |-
  &eMasz &c20 &esekund aby wybrac imie, napisz je na czacie.
  &eNapisz &2Cancel &eaby anulowac wybieranie nazwy.
Timed-Out: '&cCzas minal, nazwa nie zostala zmieniona!'
Cancel-Rename-Pet: '&cAnulowano nazywanie zwierzatka.'
Rocket-Countdown: '&c&lRAKIETA WYSTARTUJE ZA {TIMER} {SECOND}!'
Rocket-Lift-Off: '&a&lSTART!'
Enabled-Self-Morph-View: '{PREFIX}&eWlaczyles widok wlasnych przemian'
Disabled-Self-Morph-View: '{PREFIX}&eWylaczyles widok wlasnych przemian!'
Enabled-Bypass-Cooldown: '{PREFIX}&eWlaczyles ignorowanie czasu oczekiwania.'
Disabled-Bypass-Cooldown: '{PREFIX}&eWylaczyles ignorowanie czasu oczekiwania.'
Enabled-Random-Mystery-Vault-Animation: '&eUstawiles losowa animacje'
Disabled-Random-Mystery-Vault-Animation: '&cWylaczyles losowa aniamcje'
Disabled-Command-While-Cosmetics-Activated: '{PREFIX}&cNie mozesz uzyc tej komendy
  kiedy kosmetyki sa aktywowane!'
Invalid-Type: '{PREFIX}&cTen {TYPE}, ktorego uzyles jest nieprawidlowy!'
Type-Is-Not-Enabled: '{PREFIX}&cTen {TYPE} nie jest wlaczony!'
Turn-Off-Bumblebee-Song: '{PREFIX}&cPiosenka Bumblebee zostala wylaczona!'
Playing-Song: '{RANDOM_COLOR}Teraz Gramy: {SONG}'
Only-Boolean-Value-Can-Be-Accepted: '&cTylko logiczne typy wartosci sa akceptowane!'
Required-Time-Format: '{PREFIX}&cWypelnij prawidlowem formatem czasu! (''h'' dla godzin,''d''
  dla dni, ''m'' dla miesiecy).'
Required-Full-Data: '{PREFIX}&cUpewnij sie ze nie brakuje zadnych danych.'
Already-Activate-One: '{PREFIX}&cJuz posiadasz aktywowany gadzet {GADGET}! Sproboj
  ponownie pozniej.'
Gadget-Activated-In-Same-Area: '{PREFIX}&cJakis gadzet jest juz aktywowany w tej strefie!
  Sproboj gdzie indziej.'
Enabled: '&cWłączone'
Disabled: '&cWyłączone'
Cooldown-Bypass: Cooldown Bypass
Self-Morph-View: Self Morph View
Unequip-Cosmetics-Due-To-Low-TPS: '&cKostemtyki zostaly wylaczone przez niskie TPSy
  serwera.'
Disable-Usage-Of-Cosmetics: '{PREFIX}&cSorry for the inconvenience, all cosmetics
  have been disabled due to server lag.'
Not-Allow-Cosmetics-In-Region: '{PREFIX}&cYou''re not allowed to equip cosmetics in
  this region.'
Not-Allow-Hat-In-Region: '{PREFIX}&cYou''re not allowed to equip hat in this region.'
Not-Allow-Animated-Hat-In-Region: '{PREFIX}&cYou''re not allowed to equip animated
  hat in this region.'
Not-Allow-Particle-In-Region: '{PREFIX}&cYou''re not allowed to equip particle in
  this region.'
Not-Allow-Suit-In-Region: '{PREFIX}&cYou''re not allowed to equip suit in this region.'
Not-Allow-Gadget-In-Region: '{PREFIX}&cYou''re not allowed to equip gadget in this
  region.'
Not-Allow-Pet-In-Region: '{PREFIX}&cYou''re not allowed to equip pet in this region.'
Not-Allow-Miniature-In-Region: '{PREFIX}&cYou''re not allowed to equip miniature in
  this region.'
Not-Allow-Morph-In-Region: '{PREFIX}&cYou''re not allowed to morph in this region.'
Not-Allow-Banner-In-Region: '{PREFIX}&cYou''re not allowed to equip banner in this
  region.'
Not-Allow-Emote-In-Region: '{PREFIX}&cYou''re not allowed to equip emote in this region.'
Not-Allow-Cloak-In-Region: '{PREFIX}&cYou''re not allowed to equip cloak in this region.'
Not-Allow-Pet-Riding-In-Region: '{PREFIX}&cYou''re not allowed to ride your pet in
  this region.'
Second: Sekunda
Seconds: Sekundy
Minute: Minuta
Minutes: Minuty
Hour: Godzina
Hours: Godziny
Day: Dzien
Days: Dni
Loading: '&aŁadowanie'
Miniatures-Are-Disabled: '{PREFIX}&cCosmetic miniatures are disabled!'
Equip-Miniature-For-Player: '&eSpawned {MINIATURE} for &6{PLAYER}.'
Reset-Miniature: '&aDespawned your miniature.'
No-Cosmetic-Equipped: none
No-Recent-Loot-Found: none
Already-Has-Permission: '&c{PLAYER} already has this permission.'
Successful-Remove-Permission: '&eSuccessful remove the permission to access &c{TYPE}
  &efrom {PLAYER}&e.'
Failed-To-Deduct-Mystery-Dust: '{PREFIX}&cFailed to deduct your mystery dust. Please
  try again.'
No-Permission-To-Open-One-Star-Box: '{PREFIX}&cYou don''t have the required permission
  to open this box!'
No-Permission-To-Open-Two-Star-Box: '{PREFIX}&cYou don''t have the required permission
  to open this box!'
No-Permission-To-Open-Three-Star-Box: '{PREFIX}&cYou don''t have the required permission
  to open this box!'
No-Permission-To-Open-Four-Star-Box: '{PREFIX}&cYou don''t have the required permission
  to open this box!'
No-Permission-To-Open-Five-Star-Box: '{PREFIX}&cYou don''t have the required permission
  to open this box!'
No-Pet-Spawned: '{PREFIX}&cYou don''t currently have a pet spawned!'
Unlock-Pet-Before-Rename: '&c{PLAYER} needed to unlock {TYPE} pet before you can rename
  it.'
Pet-Name-In-Blacklist: '&cYou''re not allowed to set the pet to this name as it contains
  indecent text.'
No-Permission-To-Ride-Pet: '&cYou do not have the permission to ride pet!'
Not-Allowed-To-Ride-Other-Pet: '&cYou cannot ride other people''s pets!'
Request-Pet-With-Happy-Status: '&cYou must have at least one pet with a Happy status
  in order to do that.'
Click-To-Increase-Happiness: '&6Right-Click &eyour pets inside the Pets Menu to feed
  them and to increase their happiness.'
Pet-Earn-EXP: '&eYour {LEVEL} {PET_NAME} &eearned &6{EXP} EXP &efrom the pet mission!'
Pet-Level-Up: '&eYour {LEVEL} {PET_NAME} &eearned &6{EXP} EXP &efrom the pet mission!
  It leveled up.'
Send-Pet-For-Mission-Is-On-Cooldown: '&cThis is currently on cooldown. Please wait
  {COOLDOWN_MINUTES} more minutes.'
No-Permission-To-Spawn-Pet: '&cYou don''t have the permission to summon your pets!'
Pet-Stat-Fulled: '&cYour {PET_NAME} &c{STAT} is already full!'
Zero-Pet-Item-Remain: '&cThis item can be found through the &6Tajemnicza skrzynia&c!'
Ate-Food-And-Dont-Like-It: '&eYour {PET_NAME} &eate a &a{ITEM}&e. They don''t like
  it very much. (&a+{INCREMENT} &6Hunger&e)'
Ate-Food-And-Like-It: '&eYour {PET_NAME} &eate a &a{ITEM}&e. They like it! (&a+{INCREMENT}
  &6Hunger&e)'
Ate-Food-And-Really-Like-It: '&eYour {PET_NAME} &eate a &a{ITEM}&e. They really like
  it! (&a+{INCREMENT} &6Hunger&e)'
Ate-Favourite-Food: '&eYour {PET_NAME} &eate a &a{ITEM}&e. It''s their favourite food!
  (&a+{INCREMENT} &6Hunger&e)'
Drank-Drink-And-Dont-Like-It: '&eYour {PET_NAME} &edrank a &a{ITEM}&e. They don''t
  like it very much. (&a+{INCREMENT} &6Thirst&e)'
Drank-Drink-And-Like-It: '&eYour {PET_NAME} &edrank a &a{ITEM}&e. They like it! (&a+{INCREMENT}
  &6Thirst&e)'
Drank-Drink-And-Really-Like-It: '&eYour {PET_NAME} &edrank a &a{ITEM}&e. They really
  like it! (&a+{INCREMENT} &6Thirst&e)'
Drank-Favourite-Drink: '&eYour {PET_NAME} &edrank a &a{ITEM}&e. It''s their favourite
  drink! (&a+{INCREMENT} &6Thirst&e)'
Played-Toy-And-Dont-Like-It: '&eYour {PET_NAME} &eplayed with a &a{ITEM}&e. They don''t
  like it very much. (&a+{INCREMENT} &6Exercise&e)'
Played-Toy-And-Like-It: '&eYour {PET_NAME} &eplayed with a &a{ITEM}&e. They like it!
  (&a+{INCREMENT} &6Exercise&e)'
Played-Toy-And-Really-Like-It: '&eYour {PET_NAME} &eplayed with a &a{ITEM}&e. They
  really like it! (&a+{INCREMENT} &6Exercise&e)'
Played-Favourite-Toy: '&eYour {PET_NAME} &eplayed with a &a{ITEM}&e. It''s their favourite
  toy! (&a+{INCREMENT} &6Exercise&e)'
Added-Pet-Item: '{PREFIX}&eYou''ve successfully added &6{AMOUNT} &e{PET_ITEM} &epet
  item to &6{PLAYER}&e.'
Received-Pet-Item: '{PREFIX}&eYou''ve received &6{AMOUNT} &e{PET_ITEM} &epet item
  from &6{PLAYER}&e.'
Removed-Pet-Item: '{PREFIX}&eYou''ve removed &6{AMOUNT} &e{PET_ITEM} &epet item from
  &6{PLAYER}&e.'
Removed-Pet-Item-From-Player: '{PREFIX}&6{AMOUNT} &e{PET_ITEM} &ehas been removed
  from your pet items.'
Set-Pet-Item: '{PREFIX}&eYou''ve set &6{AMOUNT} &e{PET_ITEM} &epet item for &6{PLAYER}&e.'
Set-Player-Pet-Item: '{PREFIX}&eYour &e{PET_ITEM} &epet item have been set to &6{AMOUNT}&e.'
Cosmetic-Reset-Completed: '&aCosmetic reset completed.'

```

PLIK MYSTERY BOXES.YML

```
Mystery-Boxes:
  Enabled: true
  Loots-Can-Be-Found:
    Hats: true
    Animated Hats: true
    Particles: true
    Suits: true
    Gadgets: true
    Pets: true
    Miniatures: true
    Banners: true
    Morphs: true
    Emotes: true
    Cloaks: true
  Chances:
    One-Star:
      Common: 70
      Rare: 15
      Epic: 10
      Legendary: 5
    Two-Star:
      Common: 70
      Rare: 18
      Epic: 12
      Legendary: 6
    Three-Star:
      Common: 58
      Rare: 20
      Epic: 15
      Legendary: 7
    Four-Star:
      Common: 52
      Rare: 22
      Epic: 18
      Legendary: 8
    Five-Star:
      Rare: 40
      Epic: 50
      Legendary: 10
  Rarity:
    Common: '&aPospolite'
    Rare: '&9Rzadkie'
    Epic: '&5Epickie'
    Legendary: '&6Legendarne'
  Execute-Command:
    Enabled: true
    Command: lp user {PLAYER} permission set {PERMISSION}
  Found-Loot:
    Common:
      Give-Pet-Items:
        Enabled: true
        Min: 20
        Max: 30
      Play-Sound:
        Sound: ENTITY_CHICKEN_EGG
      Send-Message:
        Enabled: true
        Message:
        - '&a&l▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬'
        - '                &a&lTajemnicza skrzynia'
        - ''
        - '     &fZwykłe znalezisko:'
        - '     &a&l{LOOT}'
        - ''
        - '&a&l▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬'
    Rare:
      Give-Pet-Items:
        Enabled: true
        Min: 25
        Max: 35
      Play-Sound:
        Enabled: true
        Sound: ENTITY_VILLAGER_AMBIENT
      Send-Message:
        Enabled: true
        Message:
        - '&9&l▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬'
        - '                &9&lTajemnicza skrzynia'
        - ''
        - '     &fRzadkie znalezisko:'
        - '     &9&l{LOOT}'
        - ''
        - '&9&l▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬'
    Epic:
      Give-Pet-Items:
        Enabled: true
        Min: 35
        Max: 40
      Play-Sound:
        Enabled: true
        Sound: ENTITY_PLAYER_LEVELUP
      Send-Message:
        Enabled: true
        Message:
        - '&5&l▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬'
        - '                &5&lTajemnicza skrzynia'
        - ''
        - '     &fEpickie znalezisko:'
        - '     &d&l{LOOT}'
        - ''
        - '&5&l▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬'
    Legendary:
      Give-Pet-Items:
        Enabled: true
        Min: 35
        Max: 45
      Play-Sound:
        Enabled: true
        Sound: ENTITY_ENDER_DRAGON_AMBIENT
      Send-Message:
        Enabled: true
        Message:
        - '&6&l▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬'
        - '                &6&lTajemnicza skrzynia'
        - ''
        - '     &fLegendarne znalezisko:'
        - '     &e&l{LOOT}'
        - ''
        - '&6&l▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬'
  Already-Had-Loot:
    Common:
      Give-Mystery-Dust:
        Enabled: true
        Min: 1
        Max: 3
      Send-Message:
        Enabled: false
        Message:
        - '&7Już posiadasz &aPospolity &e{LOOT} &7wiec'
        - '&7Dostajesz &e{MYSTERY_DUST}x monet&7.'
      Execute-Command:
        Enabled: false
        Command: points give {PLAYER} 100
    Rare:
      Give-Mystery-Dust:
        Enabled: true
        Min: 4
        Max: 8
      Send-Message:
        Enabled: false
        Message:
        - '&7Już posiadasz &9Rzadki &e{LOOT} &7wiec'
        - '&7Dostajesz &e{MYSTERY_DUST}x monet&7.'
      Execute-Command:
        Enabled: false
        Command: points give {PLAYER} 500
    Epic:
      Give-Mystery-Dust:
        Enabled: true
        Min: 9
        Max: 25
      Send-Message:
        Enabled: false
        Message:
        - '&7Już posiadasz &5Epicki &e{LOOT} &7wiec'
        - '&7Dostajesz &e{MYSTERY_DUST}x monet&7.'
      Execute-Command:
        Enabled: false
        Command: points give {PLAYER} 1000
    Legendary:
      Give-Mystery-Dust:
        Enabled: true
        Min: 26
        Max: 36
      Send-Message:
        Enabled: false
        Message:
        - '&7Już posiadasz &7Legendarny &e{LOOT} &7wiec'
        - '&7Dostajesz &e{MYSTERY_DUST}x monet&7.'
      Execute-Command:
        Enabled: false
        Command: points give {PLAYER} 10000
  Holograms:
    Found-Loot:
      Common: '&aPospolity {LOOT}'
      Rare: '&9Rzadki {LOOT}'
      Epic: '&5Epicki {LOOT}'
      Legendary: '&6Legendarny {LOOT}'
    Mystery-Vault:
      Line-1: '&bTajemnicza skrzynia'
      Line-2: '&e&lPRAWY PRZYCISK'
    Individual-Holograms:
      Enabled: true
      Available-Mystery-Boxes:
      - '&cMasz {MYSTERY_BOXES} skrzynek'
      - '&eMasz {MYSTERY_BOXES} skrzynek'
      - '&aMasz {MYSTERY_BOXES} skrzynek'
      - '&9Masz {MYSTERY_BOXES} skrzynek'
      - '&dMasz {MYSTERY_BOXES} skrzynek'
      Zero-Mystery-Box-Available: '&cNie masz skrzynek :('
    Hologram-Height: 1.21
  Broadcast:
    Opening-Mystery-Box:
      Enabled: true
      Message: '&6[Tajemnicza skrzynia] &7{PLAYER} &rotwiera Mystery Boxa.'
    Found-Loot:
      Common:
        Enabled: true
        Message: '&6[Tajemnicza skrzynia] &7{PLAYER} &rznalazl &aZwykle {LOOT}&r!'
      Rare:
        Enabled: true
        Message: '&6[Tajemnicza skrzynia] &7{PLAYER} &rznalazl &9Rzadkie {LOOT}&r!'
      Epic:
        Enabled: true
        Message: '&6[Tajemnicza skrzynia] &7{PLAYER} &rznalazl &5Epickie {LOOT}&r!'
      Legendary:
        Enabled: true
        Message: '&6[Tajemnicza skrzynia] &7{PLAYER} &rznalazl &6Legendarne {LOOT}&r!'
    Found-Mystery-Box:
      One-Star:
        Enabled: true
        Message: '{PLAYER} &fznalazl &e✰&7✰✰✰✰ &fMystery Box!'
      Two-Star:
        Enabled: true
        Message: '{PLAYER} &fznalazl &e&e✰✰&7✰✰✰ &fMystery Box!'
      Three-Star:
        Enabled: true
        Message: '{PLAYER} &fznalazl &e✰✰✰&7✰✰ &fMystery Box!'
      Four-Star:
        Enabled: true
        Message: '{PLAYER} &fznalazl &e&e✰✰✰✰&7✰ &fMystery Box!'
      Five-Star:
        Enabled: true
        Message: '{PLAYER} &fznalazl &e&e✰✰✰✰✰ &fMystery Box!'
  Mystery-Boxes-Reward:
    Enabled: true
    Allow-AFK: false
    Chance-To-Get-Mystery-Box: 75
    Chance:
      One-Star: 5
      Two-Star: 10
      Three-Star: 60
      Four-Star: 20
      Five-Star: 5
    Expiry-Date-In-Days: 7
    Play-Time:
      Hours: 0
      Minutes: 40
      Seconds: 0
    Enabled-Worlds:
    - '*'
    Message:
      One-Star: '&7Znalazłes &e✰&7✰✰✰✰ &6Tajemnicza skrzynie'
      Two-Star: '&7Znalazłes &e✰✰&7✰✰✰ &6Tajemnicza skrzynie'
      Three-Star: '&7Znalazłes &e✰✰✰&7✰✰ &6Tajemnicza skrzynie'
      Four-Star: '&7Znalazłes &e✰✰✰✰&7✰ &6Tajemnicza skrzynie'
      Five-Star: '&7Znalazłes &e✰✰✰✰✰ &6Tajemnicza skrzynie'
  JSON-Messages:
    Found-Mystery-Box:
      One-Star:
        Name: '&6Tajemnicza skrzynia'
        Lore:
        - '&7Rzadkosc: &e✰&7✰✰✰✰'
        - '&7Mozesz znalesc tego &bMystery Boxa '
        - '&7Grajac na naszym serwerze.'
        Message:
        - '&6tajemnicza skrzynia'
        - '&7Rzadkosc: &e✰&7✰✰✰✰'
        - '&7Mozesz znalesc ta &6Tajemnicza skrzynie'
        - '&7Grajac na naszym serwerze.'
      Two-Star:
        Name: '&6Tajemnicza skrzynia'
        Lore:
        - '&7Rzadkosc: &e✰✰&7✰✰✰'
        - '&7Mozesz znalesc tego &bMystery Boxa '
        - '&7Grajac na naszym serwerze.'
        Message:
        - '&6Tajemnicza skrzynia'
        - '&7Rzadkosc: &e✰✰&7✰✰✰'
        - '&7Mozesz znalesc ta &6Tajemnicza skrzynie'
        - '&7Grajac na naszym serwerze.'
      Three-Star:
        Name: '&6tajemnicza skrzynia'
        Lore:
        - '&7Rzadkosc: &e✰✰✰&7✰✰'
        - '&7Mozesz znalesc tego &bMystery Boxa '
        - '&7Grajac na naszym serwerze.'
        Message:
        - '&6Tajemnicza skrzynia'
        - '&7Rzadkosc: &e✰✰✰&7✰✰'
        - '&7Mozesz znalesc ta &6Tajemnicza skrzynie'
        - '&7Grajac na naszym serwerze.'
      Four-Star:
        Name: '&6Tajemnicza skrzynia'
        Lore:
        - '&7Rzadkosc: &e✰✰✰✰&7✰'
        - '&7Mozesz znalesc ta &6Tajemnicza skrzynie'
        - '&7Grajac na naszym serwerze.'
        Message:
        - '&6Tajemnicza skrzynia'
        - '&7Rzadkosc: &e✰✰✰✰&7✰'
        - '&7Mozesz znalesc ta &6Tajemnicza skrzynie'
        - '&7Grajac na naszym serwerze.'
      Five-Star:
        Name: '&6Tajemnicza skrzynia'
        Lore:
        - '&7Rzadkosc: &e✰✰✰✰✰'
        - '&7Mozesz znalesc tego &bMystery Boxa '
        - '&7Grajac na naszym serwerze.'
        Message:
        - '&6tajemnicza skrzynia'
        - '&7Rzadkosc: &e✰✰✰✰✰'
        - '&7Mozesz znalesc ta &6Tajemnicza skrzynie'
        - '&7Grajac na naszym serwerze.'
    Found-Loot:
      Common:
        Name: '&aZwykle {LOOT}'
        Lore:
        - '&7Typ: {CATEGORY}'
        - '&7Rzadkosc: &aZwykle'
        Message:
        - '&aCommon {LOOT}'
        - '&7Typ: {CATEGORY}'
        - '&7Rzadkosc: &aZwykle'
      Rare:
        Name: '&9Rzadkie {LOOT}'
        Lore:
        - '&7Typ: {CATEGORY}'
        - '&7Rzadkosc: &9Rzadka'
        Message:
        - '&9Rare {LOOT}'
        - '&7Typ: {CATEGORY}'
        - '&7Rzadkosc: &9Rzadka'
      Epic:
        Name: '&5Epickie {LOOT}'
        Lore:
        - '&7Typ: {CATEGORY}'
        - '&7Rzadkosc: &5Epickie'
        Message:
        - '&5Epic {LOOT}'
        - '&7Typ: {CATEGORY}'
        - '&7Rzadkosc: &5Epickie'
      Legendary:
        Name: '&6Legendarne {LOOT}'
        Lore:
        - '&7Typ: {CATEGORY}'
        - '&7Rzadkosc: &6Legendarne'
        Message:
        - '&6Legendary {LOOT}'
        - '&7Typ: {CATEGORY}'
        - '&7Rzadkosc: &6Legendarne'
    Mystery-Dust:
      Message:
      - '&6Tajemniczy proszek'
      - '&7Możesz go użyc do kupienia'
      - '&6Tajemniczej skrzyni&7!'
    Pet-Items:
      Message:
      - '&7Zobacz swoje &eGadżety &7oraz'
      - '&7kliknij na nie by przenieść'
      - '&7je do ekwipunku.'
  Types:
    Normal-Mystery-Box:
      Name: '&6Tajemnicza skrzynia'
      Material: ENDER_CHEST
      Lore:
        Expiry-Date: '&cWygasa za {EXPIRY_DATE}'
        Never-Expired: '&7Nie wygasa.'
        Quality:
          One-Star:
          - '&eTa tajemnicza skrzynia zawiera jedno:'
          - ''
          - '&aZwykle {ITEM_ONE}'
          - '&aZwykle {ITEM_TWO}'
          - '&aZwykle {ITEM_THREE}'
          - '&aZwykle {ITEM_FOUR}'
          - '&9Zwykle {ITEM_FIVE}'
          - '&5Epickie {ITEM_SIX}'
          - '&6Legendarne {ITEM_SEVEN}'
          - ''
          - '&7Jakosc: &e✰&7✰✰✰✰'
          - '{EXPIRY_DATE}'
          - ''
          - '&eKliknij, aby otworzyc'
          Two-Star:
          - '&eTa tajemnicza skrzynia zawiera jedno:'
          - ''
          - '&aZwykle {ITEM_ONE}'
          - '&aZwykle {ITEM_TWO}'
          - '&aZwykle {ITEM_THREE}'
          - '&9Rzadkie {ITEM_FOUR}'
          - '&9Rzadkie {ITEM_FIVE}'
          - '&5Epickie {ITEM_SIX}'
          - '&6Legendarne {ITEM_SEVEN}'
          - ''
          - '&7akosc: &e✰✰&7✰✰✰'
          - '{EXPIRY_DATE}'
          - ''
          - '&eKliknij, aby otworzyc'
          Three-Star:
          - '&eTa tajemnicza skrzynia zawiera jedno:'
          - ''
          - '&aZwykle {ITEM_ONE}'
          - '&aZwykle {ITEM_TWO}'
          - '&9Rzadkie {ITEM_THREE}'
          - '&9Rzadkie {ITEM_FOUR}'
          - '&5Epickie {ITEM_FIVE}'
          - '&5Epickie {ITEM_SIX}'
          - '&6Legendarne {ITEM_SEVEN}'
          - ''
          - '&7Jakosc: &e✰✰✰&7✰✰'
          - '{EXPIRY_DATE}'
          - ''
          - '&eKliknij, aby otworzyc!'
          Four-Star:
          - '&eTa tajemnicza skrzynia zawiera jedno:'
          - ''
          - '&aZwykle {ITEM_ONE}'
          - '&9Rzadkie {ITEM_TWO}'
          - '&5Epickie {ITEM_THREE}'
          - '&5Epickie {ITEM_FOUR}'
          - '&6Legendarne {ITEM_FIVE}'
          - '&6Legendarne {ITEM_SIX}'
          - '&6Legendarne {ITEM_SEVEN}'
          - ''
          - '&7Jakosc: &e????&7?'
          - '{EXPIRY_DATE}'
          - ''
          - '&eKliknij, aby otworzyc'
          Five-Star:
          - '&eTa tajemnicza skrzynia zawiera jedno:'
          - ''
          - '&9Rzadkie {ITEM_ONE}'
          - '&5Epickie {ITEM_TWO}'
          - '&5Epickie {ITEM_THREE}'
          - '&6Legendarne {ITEM_FOUR}'
          - '&6Legendarne {ITEM_FIVE}'
          - '&6Legendarne {ITEM_SIX}'
          - '&6Legendarne {ITEM_SEVEN}'
          - ''
          - '&7Jakosc: &e✰✰✰✰✰'
          - '{EXPIRY_DATE}'
          - ''
          - '&eKliknij, aby otworzyc'
    Gifted-Mystery-Box:
      Name: '&ePrezent &6Tajemnicza skrzynia'
      Material: ENDER_CHEST
      Lore:
        One-Star:
        - '&eTa tajemnicza skrzynia zawiera jedno:'
        - ''
        - '&aZwykle {ITEM_ONE}'
        - '&aZwykle {ITEM_TWO}'
        - '&aZwykle {ITEM_THREE}'
        - '&aZwykle {ITEM_FOUR}'
        - '&9Rzadkie {ITEM_FIVE}'
        - '&5Epickie {ITEM_SIX}'''
        - '&6Legendarne {ITEM_SEVEN}'
        - ''
        - '&7Jakosc: &e✰&7✰✰✰✰'
        - ''
        - '&7Otrzymales ten gift od:'
        - '&7{SENDER}'
        - ''
        - '&eKliknij, aby otworzyc!'
        Two-Star:
        - '&eTa tajemnicza skrzynia zawiera jedno:'
        - ''
        - '&aZwykle {ITEM_ONE}'
        - '&aZwykle {ITEM_TWO}'
        - '&aZwykle {ITEM_THREE}'
        - '&9Rzadkie {ITEM_FOUR}'
        - '&9Rzadkie {ITEM_FIVE}'
        - '&5Epickie {ITEM_SIX}'
        - '&6Legendarne {ITEM_SEVEN}'
        - ''
        - '&7Jakosc: &e✰✰&7✰✰✰'
        - ''
        - '&7Otrzymales ten gift od:'
        - '&7{SENDER}'
        - ''
        - '&eKliknij, aby otworzyc!'
        Three-Star:
        - '&eTa tajemnicza skrzynia zawiera jedno:'
        - ''
        - '&aZwykle {ITEM_ONE}'
        - '&aZwykle {ITEM_TWO}'
        - '&9Rzadkie {ITEM_THREE}'
        - '&9Rzadkie {ITEM_FOUR}'
        - '&5Epickie {ITEM_FIVE}'
        - '&5Epickie {ITEM_SIX}'
        - '&6Legendarne {ITEM_SEVEN}'
        - ''
        - '&7Jakosc: &e✰✰✰&7✰✰'
        - ''
        - '&7Otrzymales ten gift od:'
        - '&7{SENDER}'
        - ''
        - '&eKliknij, aby otworzyc!'
        Four-Star:
        - '&eTa tajemnicza skrzynia zawiera jedno:'
        - ''
        - '&aZwykle {ITEM_ONE}'
        - '&9Rzadkie {ITEM_TWO}'
        - '&5Epickie {ITEM_THREE}'
        - '&5Epickie {ITEM_FOUR}'
        - '&6Legendarne {ITEM_FIVE}'
        - '&6Legendarne {ITEM_SIX}'
        - '&6Legendarne {ITEM_SEVEN}'
        - ''
        - '&7Jakosc: &e✰✰✰✰&7✰'
        - ''
        - '&7Otrzymales ten gift od:'
        - '&7{SENDER}'
        - ''
        - '&eKliknij, aby otworzyc!'
        Five-Star:
        - '&eTa tajemnicza skrzynia zawiera jedno:'
        - ''
        - '&9Rzadkie {ITEM_ONE}'
        - '&5Epickie {ITEM_TWO}'
        - '&5Epickie {ITEM_THREE}'
        - '&6Legendarne {ITEM_FOUR}'
        - '&6Legendarne {ITEM_FIVE}'
        - '&6Legendarne {ITEM_SIX}'
        - '&6Legendarne {ITEM_SEVEN}'
        - ''
        - '&7Jakosc: &e✰✰✰✰✰'
        - ''
        - '&7Otrzymales ten gift od:'
        - '&7{SENDER}'
        - ''
        - '&eKliknij, aby otworzyc!'
    Crafted-Mystery-Box:
      One-Star:
        Name: '&6Tajemnnicza skrzynia #1'
        Material: ENDER_CHEST
        Lore:
        - '&eTa tajemnicza skrzynia zawiera jedno:'
        - ''
        - '&aZwykle {ITEM_ONE}'
        - '&aZwykle {ITEM_TWO}'
        - '&aZwykle {ITEM_THREE}'
        - '&aZwykle {ITEM_FOUR}'
        - '&9Rzadkie {ITEM_FIVE}'
        - '&5Epickie {ITEM_SIX}'
        - '&6Legendarne {ITEM_SEVEN}'
        - ''
        - '&7Jakosc: &e✰&7✰✰✰✰'
        - ''
        - '&eKliknij, aby otworzyc!'
      Two-Star:
        Name: '&6Tajemnnicza skrzynia #2'
        Material: ENDER_CHEST
        Lore:
        - '&eTa tajemnicza skrzynia zawiera jedno:'
        - ''
        - '&aZwykle {ITEM_ONE}'
        - '&aZwykle {ITEM_TWO}'
        - '&aZwykle {ITEM_THREE}'
        - '&9Rzadkie {ITEM_FOUR}'
        - '&9Rzadkie {ITEM_FIVE}'
        - '&5Epickie {ITEM_SIX}'
        - '&6Legendarne {ITEM_SEVEN}'
        - ''
        - '&7Jakosc: &e✰✰&7✰✰✰'
        - ''
        - '&eKliknij, aby otworzyc!'
      Three-Star:
        Name: '&6Tajemnnicza skrzynia #3'
        Material: ENDER_CHEST
        Lore:
        - '&eTa tajemnicza skrzynia zawiera jedno:'
        - ''
        - '&aZwykle {ITEM_ONE}'
        - '&aZwykle {ITEM_TWO}'
        - '&9Rzadkie {ITEM_THREE}'
        - '&9Rzadkie {ITEM_FOUR}'
        - '&5Epickie {ITEM_FIVE}'
        - '&5Epickie {ITEM_SIX}'
        - '&6Legendarne {ITEM_SEVEN}'
        - ''
        - '&7Jakosc: &e✰✰✰&7✰✰'
        - ''
        - '&eKliknij, aby otworzyc!'
      Four-Star:
        Name: '&6Tajemnnicza skrzynia #4'
        Material: ENDER_CHEST
        Lore:
        - '&eTa tajemnicza skrzynia zawiera jedno:'
        - ''
        - '&aZwykle {ITEM_ONE}'
        - '&9Rzadkie {ITEM_TWO}'
        - '&5Epickie {ITEM_THREE}'
        - '&5Epickie {ITEM_FOUR}'
        - '&6Legendarne {ITEM_FIVE}'
        - '&6Legendarne {ITEM_SIX}'
        - '&6Legendarne {ITEM_SEVEN}'
        - ''
        - '&7Jakosc: &e✰✰✰✰&7✰'
        - ''
        - '&eKliknij, aby otworzyc!'
      Five-Star:
        Name: '&6Tajemnnicza skrzynia #5'
        Material: ENDER_CHEST
        Lore:
        - '&eTa tajemnicza skrzynia zawiera jedno:'
        - ''
        - '&9Rzadkie {ITEM_ONE}'
        - '&5Epickie {ITEM_TWO}'
        - '&5Epickie {ITEM_THREE}'
        - '&6Legendarne {ITEM_FOUR}'
        - '&6Legendarne {ITEM_FIVE}'
        - '&6Legendarne {ITEM_SIX}'
        - '&6Legendarne {ITEM_SEVEN}'
        - ''
        - '&7Jakosc: &e✰✰✰✰✰'
        - ''
        - '&eKliknij, aby otworzyc!'

```

PLIK ANIMATIONS.YML

```
Animations:
  None:
    Name: '&6Efekt: &8Brak'
    Material: BARRIER
    Enabled: true
    Mini-Block:
      Material: ENDER_CHEST
    Lore:
    - '&7Ustaw efekt otwerania'
    - '&7skrzyni na &8Brak'
  Normal:
    Name: '&6Efekt: &aNormalny'
    Material: ENDER_CHEST
    Enabled: true
    Mini-Block:
      Material: ENDER_CHEST
    Lore:
    - '&7Ustaw efekt otwerania'
    - '&7skrzyni na &aNormalny'
  CountDown:
    Name: '&6Animation: Countdown'
    Material: CLOCK
    Enabled: false
    Mini-Block:
      Material: ENDER_CHEST
    Lore:
    - '&7Set your mystery vault'
    - '&7animation to &aCountdown&7.'
  Star:
    Name: '&6Efekt: &aGwiazda'
    Material: NETHER_STAR
    Enabled: true
    Mini-Block:
      Material: ENDER_CHEST
    Mystery-Box-Quality-Block:
      Material: NETHER_STAR
    Lore:
    - '&7Ustaw efekt otwerania'
    - '&7skrzyni na &aGwiazda'
  Crafting:
    Name: '&6Efekt: &6Crafting'
    Material: CRAFTING_TABLE
    Enabled: true
    Mini-Block:
      Material: ENDER_CHEST
    Mystery-Box-Quality-Block:
      Material: CRAFTING_TABLE
      Rotational-Angle:
        X: 270
        Y: 0
        Z: 45
    Lore:
    - '&7Ustaw efekt otwerania'
    - '&7skrzyni na &6Crafing'
  Summer:
    Name: '&6Efekt: &eWakacje'
    Material: SUNFLOWER
    Enabled: true
    Mini-Block:
      Material: head:5a5ab05ea254c32e3c48f3fdcf9fd9d77d3cba04e6b5ec2e68b3cbdcfac3fd
    Mystery-Box-Quality-Block:
      Material: SUNFLOWER
    Lore:
    - '&7Ustaw efekt otwerania'
    - '&7skrzyni na &eWakacje'
  Halloween:
    Name: '&6Efekt: &cHallowen'
    Material: JACK_O_LANTERN
    Enabled: true
    Mini-Block:
      Material: JACK_O_LANTERN
    Lore:
    - '&7Ustaw efekt otwerania'
    - '&7skrzyni na &cHallowen'
  Holiday:
    Name: '&6Efekt: &bŚwięta'
    Material: SNOWBALL
    Enabled: true
    Mini-Block:
      Material: head:f5612dc7b86d71afc1197301c15fd979e9f39e7b1f41d8f1ebdf8115576e2e
    Mystery-Box-Quality-Block:
      Material: SNOWBALL
    Lore:
    - '&7Ustaw efekt otwerania'
    - '&7skrzyni na &bŚwięta'
