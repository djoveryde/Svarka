## Building Swarka
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
