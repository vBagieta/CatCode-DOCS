# Spolszczenie [GadgetsMenu Premium](https://www.spigotmc.org/resources/gadgetsmenu-1-8-1-18-1-premium.62831/) przez [vBagieta](https://github.com/vBagieta)
### Spolszczenie nie jest gotowe w 100%!
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
      Mystery-Box-Information:
        Name: '&6Informacje'
        Texture: http://textures.minecraft.net/texture/83d874eb8c4c697b3f832bd874426fdf6d21bae339f31711081fde59838386e1
        Slot: 50
        Loot-Contain-Rarity: true
        Lore:
        - '&7W &6Tajemniczych skrzyniach'
        - '&7Znajdziesz wiele dodatków'
        - '&6Tajemnicze skrzynie &7Zdoywasz'
        - '&7Grająć na serwerze!'
        - ''
        - '&7Twoj ostatni znaleziony loot:'
        - '&e1. &e{RECENT_LOOT_1}'
        - ''
        - '&ePosiadasz: &6{MYSTERY_BOXES} Tajemniczych skrzyń'
        Material: head:83d874eb8c4c697b3f832bd874426fdf6d21bae339f31711081fde59838386e1
      Craft-Mystery-Boxes:
        Name: '&6Kup tajemnicza skrzynie!'
        Texture: http://textures.minecraft.net/texture/fe35d96a6d6786fbc1cd232c3556f8a857bdeb278bd662ee387a9a3b1174e4a7
        Show: true
        Slot: 49
        Lore:
        - '&ePosiadasz: &6{MYSTERY_DUST}x &dGrzybków'
        - ''
        - '&eNacisnij aby stworzyć skrzynie!'
        Material: head:fe35d96a6d6786fbc1cd232c3556f8a857bdeb278bd662ee387a9a3b1174e4a7
      Gift-Inventory:
        Name: '&6Prezenty'
        Show: true
        Texture: http://textures.minecraft.net/texture/5e7981347b3cff63334002c914bf0420f4560c3abcd7e47bb2d0bbe3a92c25bb
        Slot: 48
        Lore:
        - '&eWysylaj prezenty do swoich przyjaciol'
        - '&ei otrzymuj unikalne nagrody!'
        - ''
        - '&ePrezenty ktore zakupisz beda'
        - '&eprzechowywane tutaj.'
        - ''
        - '&ePrezenty Wyslane: &6{GIFT_SENT}'
        - '&ePrezenty Otrzymane: &6{GIFT_RECEIVED}'
        - ''
        - '&eNacisnij aby otworzyc menu prezentow!'
        Material: head:d2ac1c51807e261c12c4f2adbad36b8b2c497c277f7223ec244cb4608c59c
      Animations:
        Name: '&6Animacje'
        Material: ENDER_PEARL
        Show: true
        Slot: 53
        Lore:
        - '&7Wybierz animacje &6Tajemniczej skrzyni'
      Open-Multiple-Boxes:
        Name: '&eOtworz Wiele Boxow'
        Material: NETHER_STAR
        Show: false
        Slot: 51
        Lore:
        - '&eOtwiera kilka &6Tajemniczych skrzyń'
        - '&ew tym samym czasie!'
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
    GUI-Name: Animacje otwierania boxa
    Items:
      Random-Mystery-Vault-Animation:
        Name: '&6Losowa animacja'
        Material: ENDER_PEARL
        Show: true
        Slot: 40
        Lore:
        - '&7Nie umiesz wybrać'
        - '&7animacji skrzyni?'
        - '&7Już nie musisz się martwić!'
        - ''
        - '&eStatus: &6{STATUS}'
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
        Name: '&aUsuń cooldown'
        Material: BARRIER
        Show: false
        Slot: 20
        Lore: ''
      Self-Morph-View:
        Name: '&aWidzenie własnych przemian'
        Material: ENDER_EYE
        Show: true
        Slot: 22
        Lore: ''
      Enabled:
        Name: '&aWłączone'
        Material: LIME_WOOL
        Lore: ''
      Disabled:
        Name: '&cWyłączone'
        Material: RED_WOOL
        Lore: ''
Items:
  Go-Back:
    Name: '&ePowrót'
    Material: ARROW
    Show: true
    Slot: 39
    Lore: ''
  Previous-Page:
    Name: '&aPoprzednia strona'
    Material: ARROW
    Slot: 39
    Lore:
    - '&eStrona &6{PAGE}'
  Next-Page:
    Name: '&aNastepna strona'
    Material: ARROW
    Slot: 41
    Lore:
    - '&eStrona &6{PAGE}'
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
  Settings:
    Name: '&6Ustawienia'
    Material: COMPARATOR
    Show: true
    Lore:
    - '&ePozwala na edycje roznych ustawien'
    Slot: 53
  MainMenu-Item:
    Name: '&6Glowne Menu'
    Material: TRAPPED_CHEST
    Show: true
    Lore:
    - '&eTajemniczego proszku: &6x{MYSTERY_DUST}'
    - '&eTajemniczych skrzyńń: &6x{MYSTERY_BOXES}'
    - ''
    - '&eBaw sie dobrze razem z naszymi!'
    - '&eprzedmiotami kosmetycznymi, mamy'
    - '&enadzieje, ze jestes zadowolony z tego pododu!'
    Slot: 49
  Morph-Slimeball:
    Name: '&6Aktywuj umiejetnosc morfowania'
  Self-Morph-View:
    Name: '&eWidzenie wlasnego morfa'
    Material: ENDER_EYE
    Show: true
    Lore:
    - '&7Status: {STATUS}'
    - ''
    - '&eNacisnij aby przelaczyc tryb widzenia wlasnego morfa.'
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
    - '&eNacisnij aby stworzyc za &6{COST}x &dGrzybków&e!'
    Play-Sound:
      Enabled: true
      Sound: ENTITY_EXPERIENCE_ORB_PICKUP
  Not-Enough-Mystery-Dust:
    Lore:
    - ''
    - '&eNacisnij aby stworzyc za &6{COST}x &dGrzybków&e!'
    Play-Sound:
      Enabled: true
      Sound: ENTITY_ENDERMAN_TELEPORT
  Enough-Mystery-Dust-To-Craft-Mystery-Box:
    Lore:
    - ''
    - '&eKoszt: &6{COST}x &dGrzybków'
    - '&eNacisnij aby stworzyc!'
    Play-Sound:
      Enabled: true
      Sound: ENTITY_EXPERIENCE_ORB_PICKUP
  Not-Enough-Mystery-Dust-To-Craft-Mystery-Box:
    Lore:
    - ''
    - '&cNacisnij aby stworzyc za &6{COST}x &dGrzybków&c!'
    - '&cMusisz miec &6{COST}x &dGrzybków&c wiecej!'
    Play-Sound:
      Enabled: true
      Sound: ENTITY_ENDERMAN_TELEPORT
  Item-Unpurchasable:
    Lore:
    - ''
    - '&cNie mozna stworzyc za pomoca &dGrzybków&c.'
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
Reset-Buttons:
  Reset-Cosmetics:
    Name: '&cResetuj kosmetyki'
    Material: RED_STAINED_GLASS
    Show: true
    Slot: 50
    Lore: ''
    Play-Sound:
      Enabled: true
      Sound: ENTITY_EXPERIENCE_ORB_PICKUP
  Reset-Hat:
    Name: '&cResetuj czapki'
    Material: RED_STAINED_GLASS
    Show: true
    Slot: 40
    Lore: ''
    Play-Sound:
      Enabled: true
      Sound: ENTITY_EXPERIENCE_ORB_PICKUP
  Reset-Animated-Hat:
    Name: '&cResetuj animowane czapki'
    Material: RED_STAINED_GLASS
    Show: true
    Slot: 40
    Lore: ''
    Play-Sound:
      Enabled: true
      Sound: ENTITY_EXPERIENCE_ORB_PICKUP
  Reset-Particle:
    Name: '&cResetuj efekty'
    Material: RED_STAINED_GLASS
    Show: true
    Slot: 40
    Lore: ''
    Play-Sound:
      Enabled: true
      Sound: ENTITY_EXPERIENCE_ORB_PICKUP
  Reset-Suit:
    Name: '&cResetuj przebrania'
    Material: RED_STAINED_GLASS
    Show: true
    Slot: 40
    Lore: ''
    Play-Sound:
      Enabled: true
      Sound: ENTITY_EXPERIENCE_ORB_PICKUP
  Reset-Gadget:
    Name: '&cResetuj gadżety'
    Material: RED_STAINED_GLASS
    Show: true
    Slot: 40
    Lore: ''
    Play-Sound:
      Enabled: true
      Sound: ENTITY_EXPERIENCE_ORB_PICKUP
  Reset-Pet:
    Name: '&cResetuj zwierzaki'
    Material: RED_STAINED_GLASS
    Show: true
    Slot: 40
    Lore: ''
    Play-Sound:
      Enabled: true
      Sound: ENTITY_EXPERIENCE_ORB_PICKUP
  Reset-Miniature:
    Name: '&cResetuj miniatórki'
    Material: RED_STAINED_GLASS
    Show: true
    Slot: 40
    Lore: ''
    Play-Sound:
      Enabled: true
      Sound: ENTITY_EXPERIENCE_ORB_PICKUP
  Reset-Morph:
    Name: '&cResetuj przemiany'
    Material: RED_STAINED_GLASS
    Show: true
    Slot: 40
    Lore: ''
    Play-Sound:
      Enabled: true
      Sound: ENTITY_EXPERIENCE_ORB_PICKUP
  Reset-Banner:
    Name: '&cResetuj banery'
    Material: RED_STAINED_GLASS
    Show: true
    Slot: 40
    Lore: ''
    Play-Sound:
      Enabled: true
      Sound: ENTITY_EXPERIENCE_ORB_PICKUP
  Reset-Emote:
    Name: '&cResetuj emotki'
    Material: RED_STAINED_GLASS
    Show: true
    Slot: 40
    Lore: ''
    Play-Sound:
      Enabled: true
      Sound: ENTITY_EXPERIENCE_ORB_PICKUP
  Reset-Cloak:
    Name: '&cResetuj płaszcze'
    Material: RED_STAINED_GLASS
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
Player-Not-Enough-MysteryDust: '{PREFIX}&cMozesz miec tylko &6{MYSTERY_DUST}x &cMystery
  Dust!'
Added-MysteryDust: '{PREFIX}&eDodales &6{MYSTERY_DUST}x &eMystery Dust graczu &6{PLAYER}&e.'
Added-MysteryDust-To-All-Players: '{PREFIX}&eDodales &6{MYSTERY_DUST}x &eMystery Dust
  dla graczy &6{ONLINE}&e.'
Check-MysteryDust: '&e{PLAYER} posiada &6{MYSTERY_DUST}x &eMystery Dust.'
Received-MysteryDust: '{PREFIX}&eOtrzymales &6{MYSTERY_DUST}x &eMystery Dust od &6{PLAYER}&e.'
Removed-MysteryDust: '{PREFIX}&eUsunales &6{MYSTERY_DUST}x &eMystery Dust graczowi
  &6{PLAYER}&e.'
Sent-MysteryDust: '{PREFIX}&eWyslales &6{MYSTERY_DUST}x &eMystery Dust do &6{PLAYER}&e.'
Set-MysteryDust: '{PREFIX}&eUstawiles Mystery Dust gracza &6{PLAYER} na &6{MYSTERY_DUST}&e.'
Only-Have-MysteryDust: '{PREFIX}&6{PLAYER} &cposiada tylko &6{MYSTERY_DUST}x &cMystery
  Dust!'
Removed-MysteryDust-From-Player: '{PREFIX}&6{MYSTERY_DUST}x 0&eMystery zostalo usuniete
  z twojego konta.'
Set-Player-MysteryDust: '{PREFIX}&eTwoj Mystery Dust zostal ustawiony na &6{MYSTERY_DUST}&e.'
Not-Enough-MysteryDust-To-Purchase: '&cNie masz wystarczająco Tajemniczego proszku!'
Pay-MysteryDust-To-Self: '{PREFIX}&cNie mozesz zaplacic Mystery Dust samemu sobie!'
Gave-Mystery-Boxes: '{PREFIX}&eDales &6{MYSTERY_BOXES}x Mystery Box &egraczu &6{PLAYER}&e.'
Gave-Mystery-Boxes-To-All-Players: '{PREFIX}&eDales &6{MYSTERY_BOXES}x Mystery Box
  &etdla graczy &6{ONLINE}&e.'
Received-Mystery-Boxes: '{PREFIX}&eOtrzymales &6{MYSTERY_BOXES}x Mystery Box &eod
  &6{PLAYER}&e.'
Added-Mystery-Vault: '{PREFIX}&aStworzono Tajemnicza skrzynia &f''{NAME}''&a.'
Redefined-Mystery-Vault: '{PREFIX}&aLokacja Tajemnicza skrzynia &f''{NAME}'' &azostala
  na nowo zdefiniowana.'
Mystery-Vault-Same-Location: '{PREFIX}&cJuz stworzyles Tajemnicza skrzynia w tym miejscu!'
Mystery-Vault-Is-Exists: '{PREFIX}&cTajemnicza skrzynia o tej nazwie juz istnieje!'
Do-Not-Have-Any-Mystery-Vault: '{PREFIX}&cNie posiadasz zadnych Tajemnicza skrzyniaow
  stworzonych!'
No-Mystery-Vault-Nearby: '{PREFIX}&cBrak Tajemnicza skrzyniaow w podanym promieniu!'
Removed-Mystery-Vault: '{PREFIX}&aUsunieto Tajemnicza skrzynia &f''{NAME}''&a.'
Mystery-Vault-Not-Found: '{PREFIX}&cNie znaleziono zadnego Tajemnicza skrzynia w tym
  miejscu!'
Mystery-Vault-Not-Found-With-Name: '{PREFIX}&cNie znaleziono zadnego Tajemnicza skrzynia
  o nazwie &f''{NAME}''&c!'
Teleport-To-Mystery-Vault: '{PREFIX}&eZostales przeteleportowany do Mystery Vualt
  o nazwie &f''{NAME}''&e.'
Open-Mystery-Vault-At-A-Time: '{PREFIX}&cTylko jeden gracz moze uzywac Tajemnicza
  skrzyniaa w tym samym czasie!'
Can-Only-Open-One-Mystery-Box: '{PREFIX}&cPoczekaj az pierwszy Mystery Box zostanie
  otwarty!'
Purchase-Cancelled: '{PREFIX}&cZakup Anulowany!'
Mystery-Boxes-Are-Disabled: '{PREFIX}&cMystery Boxy sa wylaczone!'
Crafted-Mystery-Box: '&eKupiłeś &6{NAME}&e.'
Gave-Mystery-Gifts: '{PREFIX}&eDarowales &6{GIFTS} &ePrezent/ow dla &r{PLAYER}&e.'
Received-Mystery-Gifts: '{PREFIX}&eOtrzymales &6{GIFTS} &ePrezent/ow od &r{PLAYER}&e.'
Send-A-Gift-To-Player: '&aWyslales prezent zawierajacy &65x Tajemniczych skrzyń &ado
  &r{PLAYER}&a!'
Received-Gift: '&aOtrzymales Prezent od &r{PLAYER}&a! Odwiedz &6Tajemnicza skrzynia&a,
  zeby go otworzyc!'
Mystery-Box-Was-Expired: '{PREFIX}&cTen Mystery Box jest przedawniony. Prosze otworz
  swoj Mystery Box zanim sie przedawni.'
Check-Mystery-Boxes: '&e{PLAYER} posiada &6{MYSTERY_BOXES}x &eMystery Box.'
Select-Mystery-Vault-Animation: '&eWybrales &6{ANIMATION} &edla swojej animacji TAjemniczej
  skrzyni.'
Not-Enough-Mystery-Boxes: '&cNie posiadasz wystarczajaco duzo Mystery Boxow.'
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
Enabled-Self-Morph-View: '{PREFIX}&eWlaczyles widok wlasnych morfow!'
Disabled-Self-Morph-View: '{PREFIX}&eWylaczyles widok wlasnych morfow!'
Enabled-Bypass-Cooldown: '{PREFIX}&eWlaczyles ignorowanie czasu oczekiwania.'
Disabled-Bypass-Cooldown: '{PREFIX}&eWylaczyles ignorowanie czasu oczekiwania.'
Enabled-Random-Mystery-Vault-Animation: '{PREFIX}&aWlaczyles &6Losowa Animacje &edla
  swojego Tajemnicza skrzyniaa.'
Disabled-Random-Mystery-Vault-Animation: '{PREFIX}&cWylaczyles &6Losowa Animacje &edla
  swojego Tajemnicza skrzyniaa.'
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
Enabled: Włączone
Disabled: '&cWyłączone'
Cooldown-Bypass: Cooldown Bypass
Self-Morph-View: Self Morph View
Unequip-Cosmetics-Due-To-Low-TPS: '{PREFIX}&cYour cosmetics has been unequipped due
  to server lag.'
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
Loading: '&cŁadowanie'
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
