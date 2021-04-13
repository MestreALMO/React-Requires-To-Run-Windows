<!-- GETTING STARTED -->
## Getting Started

Using React In Windows Basic Requirements:

### Prerequisites

The things you need to install the software and how to install them

* [Nodejs](https://nodejs.org/en/) - Node.js is a JavaScript runtime built on Chrome's V8 JavaScript engine.
* Chocolatey - Chocolatey is software management automation for Windows that wraps installers, executables, zips, and scripts into compiled packages.
  * To install execute the codes with a terminal (ex: In Windows use PowerShell):
    ```
    Get-ExecutionPolicy
    ```
    ```
    Set-ExecutionPolicy AllSigned
    ```
    ```
    Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
    ```
    ```
    choco
    ```
* Node.js, Yarn, Python2 e a JDK 8
  ```
  choco install -y nodejs-lts yarn python2 jdk8
  ```

</br>

## Running Code

Now the PC is ready to run/create codes.

</br>
