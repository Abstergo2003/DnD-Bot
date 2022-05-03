# dice-roller
##############################################################################################################################################################


By twój bot działał w wersji po polsku zwtczajnie podmień plik commands.json w folderze data na ten załączony tutaj


################################################################################################################################################################# 
$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$

CREATED BY: Abstergo using Discord Bot Maker

$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$
UWAGA: PRZECZYTAJ TO PRZED URUCHOMIENIEM BOTA
################################################################################################################
WSTĘP

Ten bot zawiera ulepszenia do DnD! Możesz: rzucać kostką, tworzyć własne kanały dla swoich gier (tylko dla posiadaczy specjalnej roli, pytaj admina)
i zapraszać ludzi by z tobą zagrali!

By stworzyć pokój do gry (rola 'game-master' jest wymagana)
1. wpisz /sgame 'nazwa' by stworzyć kanał i kanał głosowy oraz kanał tylko dla game mastera
2. by dodać urzytkownika wpisz /add @'nick' (nie przejmuj się nikt po za tobą nie będzie w stanie używać tych komend)
3. by wyrzucic urzytkownika wpisz /remove @'nick'
4. by zakończyć grę (i usunąć kanał) wpisz /dgame na tym kanale

Istnieje specjalny kanał widzoczny tylko dla ludzi którzy szukają dla siebie gry (mają rolę 'invite-me')
1. by zdobyć rolę wpisz /waiting
2. by jej się pozbyć wpisz /notwaiting

Reagowanie na wiadomość wysłaną na kanał 'class' da ci rolę w zależności od emotki 
(używaj by zaznaczyć twoją ulubioną klasę postaci)
1. by pozbyć się roli (już nie lubisz tej klasy) wpisz /del 'Rola' (uważaj na wielkie litery)
!!!UWAGA!!!: by ta opcja działałą serwer potrzebuje emoji nazwanych tak ja na wiadomosci [czyli wszystkie klasy postaci (bez tych z dodatków), pamiętaj by wszystko napisać małą literą]
!!!UWAGA!!!: za każdym razem gdy bot jest restartowany wysyała wiadomość na kanał class jeszcze raz

Randomizery:
/rfight generuje losową walkę z losowymi przeciwnikami, by zobaczyć schemat losowania użyj !fhelp
/rmeet generuje randomowy quest poboczny (jego początek), by zobaczyć schemat losowania użyj !mhelp
/rdeath 'urzytkownik' wybiera losowy sposób śmierci dla jego postaci (można wpisać jego imie w sesji, nie musi być to prawdziwy urzytkownik), by zobaczyć schemat losowania użyj !dhelp
/rmname generuje losowe męskie imie
/rfname generuje losowe żeńskie imie

Rzucanie kostką
1. By rzucić kostką czworościenną użyj komendy /d4
2. By użyć jakiejkolwiek innej kostki użyj analogicznych komend
3. Dostępne kostki to 4,6,8,10,12,20,100
4. By rzucić kostką wielokrotnie użyj /md4 "ilość" (analogicznie z innymi kostkami)
5. By użyć spersonalizowanego rzutu użyj /cd "max wartość" (by urzyć jej wielokrotnie /mcd "max wartość" "ilość")
6. Każda kostka ma przypisany kolor
#################################################################################################################
Konfiguracja bota:

Muszisz zrobić to sam,
1. wejdź na https://discord.com/developers/applications
2. stwórz aplikacje bota, nazwij ją jak chcesz
3. znajdź 'app id' i 'bot token'
4. wejdź w  'lokalizacja bota'/data/settings.json
5. wprowadź dane z punktu 3. we wskazane pola
6. zapisz plik
##################################################################################################################################################################
Start twojego bota

1 metoda - na własnym komputerze (twój komputer będzi musiał cały czas działac by bot był online)(DARMOWA)

- zainstaluj node.js i uruchom go
- w konsoli wpisz: node 'lokalizacja bota'/bot.js
- gotowe
- możesz dodać bota do servera

2 metoda - na heroku (DARMOWA)
- stwórz Procfile i umieść go w lokalizacji bota
- w procfile wpisz 'worker: node bot.js'
- prześlij pliki na heroku
- zmień dyno formation na worker 
- możesz dodać bota na server

By dodać pota na server wklej ten link w przeglądarkę: https://discord.com/api/oauth2/authorize?client_id=YOUR BOT APP ID&permissions=8&scope=bot%20applications.commands
###################################################################################################################################################################

Możesz wprowadzać zmiany w moim bocie, jednak jako że zostal on stworzony przy użyciu aplikacji Discord Bot Maker, może to być ciężkie nie używając jej,
Każdy prawdziwy programista powinin raczej napisac swojego bota od zera zamiast go przerabiać

######################################################################################################################################################################