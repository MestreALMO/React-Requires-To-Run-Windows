<!-- GETTING STARTED -->

## Getting Started

Using React In Windows Basic Requirements:

### Prerequisites

The things you need to install the software and how to install them

- [Nodejs](https://nodejs.org/en/) - Node.js is a JavaScript runtime built on Chrome's V8 JavaScript engine.
- [Chocolatey](https://chocolatey.org/install) - Chocolatey is software management automation for Windows that wraps installers, executables, zips, and scripts into compiled packages.
  - To install execute the codes with a terminal (ex: In Windows use PowerShell):
    ```
    Get-ExecutionPolicy
    ```
    ```
    Set-ExecutionPolicy AllSigned
    ```
    ```
    Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
    ```
- [Node.js](https://nodejs.org/), [Yarn](https://yarnpkg.com/), [Python2](https://www.python.org/) and [JDK 8](https://www.oracle.com/java/technologies/javase/javase-jdk8-downloads.html)
  ```
  choco install -y nodejs-lts yarn python2 jdk8
  ```

### Optional

- [Visual Studio Code (VSC)](https://code.visualstudio.com/), code editor.

- [NextJS](https://nextjs.org/), React framework. Installer:
  ```
  npm i -g create-next-app
  ```

</br>

## Running Code

Now the PC is ready to run/create codes.

</br>
