# Install

## Requirements

To run PrintWeave you need to have a computer or server to host the PrintWeave software (Raspberry Pi recommended) and a supported 3d printer.

## Install

To Install the PrintWeave software intall, you have a few options:

### Donwload from NPM

1.  Download the latest release via NPM:

    ```
    npm install -g @printweave/cli
    ```
2.  Configure the PrintWeave software:

    ```
    printweave configure
    ```
3.  Start the PrintWeave server:

    ```
     printweave start
    ```

### Manual Setup

1.  Clone the repository from GitHub:

    ```bash
    git clone https://github.com/printweave/printweave.git
    ```
2.  Navigate into the repository directory:

    ```bash
    cd printweave
    ```
3.  Install the required dependencies:

    ```bash
    npm install
    ```
4.  Build the project:

    ```bash
    npm run build
    ```
5.  Start the application:

    ```bash
    npm start
    ```
