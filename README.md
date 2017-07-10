## Building Svarka (ENG)
* Checkout project
  * You can use IDE or clone from console:
  `git clone https://github.com/fewizz/Svarka.git`
* Setup
  * Setting up submodules:
  `git submodule update --init --recursive`
* Building
  * Build the project for Linux:
  `./gradlew build`
  * or for Windows:
  `./gradlew.bat build `

All builds will be in `build/distributions`

svarka-0.0.2-installer.jar - is the installer for libraries and default minecraft-server.jar

svarka-0.0.2-universal.jar - is the server we should run it

## Сборка Svarka (RUS)
* Получаем репозиторий
  * Можем использовать в IDE или в консоле:
  `git clone https://github.com/fewizz/Svarka.git`
* Установка
  * Настройка подмодулей:
  `git submodule update --init --recursive`
* Построение
  * Команда для подстроени под Linux:
  `./gradlew build`
  * или под Windows:
  `./gradlew.bat build `

Все построения будут появлятся в папке `build/distributions`

svarka-0.0.2-installer.jar - установщик, нужен для скачивания библиотек и обычного minecraft-server.jar

svarka-0.0.2-universal.jar - сам сервер, мы должны его и запускать через bat или sh
