# Compatibility Mod for Captain Sim Boeing 777/767 based on Salty
## About
This Compatibility Mod built-up project based on [Salty Simulations 747](https://github.com/saltysimulations/salty-747). 

This is an open-source modification for Captain Sim Boeing 777-200ER, Boeing 777-300ER, Boeing 777F and Boeing 767-400ER. Our goal is to make all CS aircrafts, which mainly based on the original Asobo Boeing 747 implementation flyable again. We decided implement this mod on top of Salty Simulation 747 as thier main goal is also to improve the Asobo Boeing 747 to a enjoyable level.

## Installation of CS777/CS767 Compatibility Mod

### Latest Build

[Click to download the latest masterrob94-salty-777 development build](https://github.com/RobSimulation/robsim-salty-777/releases/download/dev/masterrob94-salty-777.zip)

To install, simply copy the salty-747 and masterrob94-salty-777 folder to your community folder. 

* Microsoft Store - `C:\Users\<USERNAME>\AppData\Local\Packages\Microsoft.FlightSimulator_[]\LocalCache\Packages\Community`

* Steam - `C:\Users\<USERNAME>\AppData\Roaming\Microsoft Flight Simulator\Packages\Community`

* Boxed - `C:\Users\<USERNAME>\AppData\Local\MSFSPackages\Community`

* If you customized install location when installing MSFS (regardless of version) - `<Install Folder>\Community`


## Development
### Requirements
* IDE of your choice (e.g. VSCode)
* NodeJS LTS (e.g. version 16)

This project can also be opened using MSFS Dev Mode
### Setup your environment
Open terminal on your working directory:

`npm install`

### Edit code
Source code is located in `./PackageSources`

### Build without MSFS Package Tool (quick and easy)
`npm run build`

The generated project will be located in `./Packages`

### Build with MSFS Package Tool (less efficient)
You have 2 choices :

* Build via MSFS Dev Mode (Build All)
* Build via provided shortcut. Drag `masterrob94-salty-777.xml` to `fspackagetool.exe` Shortcut (MSFS SDK must be installed on default location)

The generated project will be located in `./Packages`
## License

The Salty Compatibility Mod for Captain Sim Boeing 777/767 is a modified version based on [Salty Simulations 747 Project](https://github.com/saltysimulations/salty-747). Therefore is this project also distributed under the GNU General Public License version 3. See [LICENSE](https://github.com/masterrob94/masterrob94-salty-777/blob/master/LICENSE).

Microsoft Flight Simulator © Microsoft Corporation. Salty Compatibility Mod for Captain Sim Boeing 777/767 was created under Microsoft's "Game Content Usage Rules" using assets from Microsoft Flight Simulator, and it is not endorsed by or affiliated with Microsoft.
