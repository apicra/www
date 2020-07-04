+ [Wersja angielska - EN](https://www.apicra.com/)

# [APIcra](https://www.apicra.com)

https://github.com/apicra

![apicra-logo.png](https://logo.apicra.com/apicra-logo.png)

## Więcej informacji

+ [Strona domowa www.apicra.com](https://www.apicra.com/)
+ [Blog](https://blog.apicra.com)

+ [apicra/www: About project, Landing page](https://github.com/apicra/www)
+ [Dokumentacja](https://docs.apicra.com)
+ [Logo](https://logo.apicra.com)


## Co to jest APIcra?

Softreck Apicra dostarcza skrypty powłoki potrzebne do przygotowania środowiska w celu uruchomienia aplikacji na systemach takich jak:
+ Linux
+ Mac OS
+ Windows

## Jak to działa?

Skrypty te są dostarczane w kilku typach:
+ archive
+ data
+ sourcecode
+ store
+ service


### archive zip
to może być program lub dane zarchiwizowane wcześniej, np backup bazy danych, wówczas np zrzut bazy danych był wykonany przez serwis backup z własnymi metodami: restore/backup
+ Unpack
+ Pack


### data/code repository /receiver /end user
Paczka plików to kod, pliki binarne lub skrypty potrzebne do przygotowania środowiska, 
zawiera metody konieczne do pobrania na dysk, zainstalowania, usunięcia i zaktualizowania plików:
+ Download
+ Update
+ Delete


### sourcecode repository, media /contributor
+ Create (only local)
+ Destroy (Delete local and remotely)
+ Publish (update, merge, deploy)


### in store librayr/software/db-data, some data or software, software package internal binary, library
case: store-from-store, sourcecode-from-download, Unpack-package-archive
+ Install
+ Remove



### service-unlimited time
Usługa już istnieje lub została wcześniej pobrana jako paczka, 
zawiera metody konieczne do uruchomienia i zatrzymania usługi oraz sprawdzenia statusu: 
case: store-from-store, sourcecode-from-download
+ Start
+ Stop
+ Restart
+ Status


### service-one time, dedicated 
Usługa wykorzystywana do wykonania jednego działania
np utworzenie kopii zapasowej lub jej odtworzenie, wówczas metody są dedykowane, mają własne nazwy w zalezności od uzycia
+ backup
+ restore


*w pierwszej wersji APIcra była zbiorem skryptów, wkrótce dużo skryptów miało podobne metody i stąd warto było je podzielić na te dwie podstawowe grupy
by łatwiej można było ustandaryzować późniejsze użycie.
 
## Python

Język python jest wyjątkowo wszechstronny w każdym tego słowa znaczeniu:

### Technologicznie
jest on wykorzystywany do tworzenia różnego rodzaju aplikacji od prostych skryptów systemowych wykonywanych na serwerze po skomplikowane obiektowe aplikacje obsługujące miliony użytkowników.

### Społecznie
Każda z kluczowych grupo społecznych od naukowej od dziecka do profesora, poprzez przemysł, finanse do sztucznej inteligencji.

### Wspieramy język python

Dlatego równolegle z językami skrypotwamy dedykowanymi dla określonych systemów, będziemy wspierać język Python, by w przyszłości na nim opierać bardziej uniwersalne i elastyczne rozwiązania.
Obecnie Python jest równie ekspresyjnym językiem jak Lua, umożliwiającym tworzenie aplikacji opartych na koprocedurach.



## The Apicra solution

is defining native OS scripts to generate enironment based on current system.
It's help to make a standarisated enironment modules, such python environment with definied versions used in your organisation

Code and Enironment are created as sepearated repository but working togheter.
To use Application, create environment and use it depends your server or local machine environment.

This is one defined layer more between application and environment to controll it not depends virtualisation in docker or another virtualisation.

[APIexec/npm-github-win: Scripts for Development, Using Github, Npmjs, Bash commands (version for windows only), version for linux npm-github-linux](https://github.com/APIexec/npm-github-win)

[apicra/docs-generator: Documentation generator for each package, automatically](https://github.com/apicra/docs-generator)

## Example with ProMaGen
+ code: [promagen/one: scripts for one project in one folder](https://github.com/promagen/one)
+ environment for windows: [promagen/windows: Environment prepared to execute ProMaGen on windows OS](https://github.com/promagen/windows)
+ environment for debian linux: [promagen/debian: Environment prepared to execute ProMaGen on Linux (Debian) OS](https://github.com/promagen/debian)



# [API Foundation](https://www.apifoundation.com)

Projekt APIcra jest wspierany przez [API Foundation](https://www.apifoundation.com)

Cel APIfoundation jest rozwój ekosystemu w celu szybszego wytwarzania oprogramowania


Obecnie istnieje kilka narzędzi od planowania po uruchamianie i utrzymanie oprogramowania:

+ [APIexec - executor library for shell scripts](https://www.apiexec.com)
+ [APIcra - shell scripts libraries](https://www.apicra.com)
+ [APIunit - definition of application, CI, CD](https://www.apiunit.com)
+ [APIbuild - build process definition, focused on quality, versioning](https://www.apibuild.com)
+ [APIsql - bazy danych, zapytania, modele](https://www.apisql.com)
+ [APIfunc - rozwiązania dla FaaS](https://www.apifunc.com)
