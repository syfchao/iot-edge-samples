# Azure IoT Edge Module Samples
This tutorial shows how to setup your IoT Edge module development environment (Windows/Ubuntu Linux), write a module, customize and initialize the IoT Edge instance. It includes samples for JavaScript, Java, and .NET modules.

If you encounter an issue related to these samples please [submit a new issue](https://github.com/Azure-Samples/iot-edge-samples/issues/new). For issues related to the IoT Edge or the packages please go to the [IoT Edge repo](https://github.com/Azure/iot-edge) and submit an issue.

<br>

## How to run the JavaScript module sample (Windows 10/Ubuntu 14+/Debian/Raspbian)
### Prerequisites
1. Install latest [Git Client](https://git-scm.com/downloads).
2. Install latest [Node LTS](https://nodejs.org) (v6.11.2).

### Raspbian:
1. Install [Raspbian-jessie](http://downloads.raspberrypi.org/raspbian/images/raspbian-2017-07-05/). 

### Quick Start
1. `git clone https://github.com/Azure-Samples/iot-edge-samples.git`
2. `cd iot-edge-samples/js/simple`
3. `npm install` to install pre-built core runtime of IoT Edge.
4. `npm run local` to start the IoT Edge with pre-defined modules (sensor and printer).

<br>

## How to run the Java module sample (Windows 10/Ubuntu 14+)
### Prerequisites
1. Install latest [Git Client](https://git-scm.com/downloads).
2. Install latest x64 version of [JRE](http://www.oracle.com/technetwork/java/javase/downloads/jre8-downloads-2133155.html).
3. Install latest [Maven](https://maven.apache.org/install.html).
### Quick Start
1. `git clone https://github.com/Azure-Samples/iot-edge-samples.git`
2. `cd iot-edge-samples/java/timer`
3. `mvn package` to build your module with all dependencies.
4. `mvn exec:exec` to start the IoT Edge with pre-defined module.

<br>

## How to run the .NET module sample (Windows 10)
### Prerequisites
1. Install latest [Git Client](https://git-scm.com/downloads).
2. Install `Visual Studio 2015` with Update 3.
### Quick Start
1. `git clone https://github.com/Azure-Samples/iot-edge-samples.git`
2. `cd iot-edge-samples\dotnet\nuget_sample\src`
3. Open the `DotnetModuleSample.sln` solution file.
4. In the `Visual Studio 2015` IDE `Solution Explorer` right click the `DotnetModuleSample` and select `properties` from the context menu.
5. Click `Debug` and update the `Executable` text box with the location and name of the executable to run by typing "**&lt;path to your output directory&gt;\gw.exe**" and update the `Application arguments:` to `module_dev_sample.json`.
6. Build the DotnetModuleSample project (`Ctrl` + `Shift` + `B`).
7. Click the `Start` button in the `Visual Studio 2015` IDE or press the `F5` key.
8. Press the `Enter` key to exit the `Azure IoT Edge` gateway process.

## How to run .NET Standard v1.3 module sample (Windows 10)
### Prerequisites
1. Install latest [Git Client](https://git-scm.com/downloads).
2. Install `Visual Studio 2017`.
### Quick Start
1. `git clone https://github.com/Azure-Samples/iot-edge-samples.git`
2. `cd iot-edge-samples\dotnetcore\nuget_sample\src`
3. Open the `NetstandardModuleSample.sln` solution file.
4. In the `Visual Studio 2017 IDE` Solution Explorer right click the `NetstandardModuleSample` and select `properties` from the context menu.
5. Click `Debug` and update the `Executable` option to `$(OutDir)gw.exe` and the `Application arguments:` to `module_dev_sample.json`.
6. Build the `NetstandardModuleSample` project (`Ctrl` + `Shift` + `B`).
7. Click the `Start` button in the `Visual Studio 2017 IDE` or press the `F5` key.
8. Press the `Enter` key to exit the `Azure IoT Edge` gateway process.