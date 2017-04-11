# Azure IoT Gateway Module Samples
This tutorial shows a JavaScript developer how to setup their module development environment (Windows/Ubuntu Linux), write a module, customize and initialize the gateway instance.

<br>

## How to run JavaScript modules (Windows 10/Ubuntu Linux 14+)
### Prerequisites
1. Install latest [Git Client](https://https://git-scm.com/downloads).
2. Install latest [Node LTS](https://nodejs.org).
### Quick Start
1. `git clone https://github.com/Azure-Samples/azure-iot-gateway-samples.git`
2. `cd azure-iot-gateway-samples/js`
3. `npm install` to install pre-built core runtime of gateway.
4. `npm run local` to start the gateway with pre-defined modules (sensor and printer).

<br>

## How to run Java modules (Windows 10/Ubuntu Linux 14+)
### Prerequisites
1. Install latest [Git Client](https://https://git-scm.com/downloads).
2. Install latest x86 version of [JRE](http://www.oracle.com/technetwork/java/javase/downloads/jre8-downloads-2133155.html).
3. Install latest [Maven](https://maven.apache.org/install.html).
### Quick Start
1. `git clone https://github.com/Azure-Samples/azure-iot-gateway-samples.git`
2. `cd java`
3. `mvn package` to build your module with all dependencies.
4. `mvn exec:exec` to start the gateway with pre-defined module.

<br>

## How to run .NET modules(Windows 10)
### Prerequisites
1. Install latest [Git Client](https://https://git-scm.com/downloads).
2. Install Visual Studio 2015 with Update 3.
### Quick Start
1. `git clone https://github.com/Azure-Samples/azure-iot-gateway-samples.git`
2. `cd dotnet`
2. Open `\DotnetModuleSample\DotnetModuleSample.sln` with and build the solution.
3. Open a command window to the project output directory (i.e. `.\DotnetModuleSample\DotnetModuleSample\bin\[Debug|Release]`).
4. Run `gw.exe module_dev_sample.json`.
5. For more information see the `README.md` file in the `.\DotnetModuleSample\DotnetModuleSample` directory.
