# BSL HTTP Server

## Project Description

This project is a simple HTTP web server built using the Bonezegei Scripting Language (BSL) and the BSL Socket Library.

The server listens on port 8080 and handles different HTTP routes. It provides a home page, an about page, and a custom 404 page for routes that do not exist.

## Installation and Setup

### 1. Install Visual Studio Code

Download and install Visual Studio Code.

### 2. Install the Bonezegei Extension

Open Visual Studio Code and go to the Extensions tab.

Search for:

`Bonezegei Scripting Language Formatter`

Install the extension.

### 3. Install the Bonezegei Interpreter

Install the Bonezegei interpreter for Windows.

To verify the installation, run:

``bash
bonezegei --version 


### 4. Install the Socket Library
    Run:
    bzg install socket

###  Run the Server
    From the project folder, run:
        bonezegei src/http.bzg

The server will run at:
    http://localhost:8080/

#### Usage

##### Home Page
    Open:
      http://localhost:8080/
This displays the default landing page.

##### About Page
    Open:
      http://localhost:8080/about
This displays information about the BSL HTTP Server project.

#### 404 Page
    Open any invalid route, for example:
      http://localhost:8080/anything
This displays the custom 404 Not Found page.

#### Screenshots
##### Home Page
##### About Page
##### 404 Page

#### Terminal

##### Project Structure
    my-bsl-http-server/
    ├── .gitattributes
    ├── LICENSE
    ├── README.md
    ├── src/
    │   └── http.bzg
    └── documentation/
        ├── home.png
        ├── about.png
        ├── 404.png
        └── terminal.png

#### License
This project uses the MIT License.