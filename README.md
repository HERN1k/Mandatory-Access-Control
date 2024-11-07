<h2 align="center">🎓 Mandatory Access Control</h2>
<div align="center">
  <img alt="Home" src="/Src/home.png" />
</div>
<p></p>

This project was created for laboratory work on the topic 

`Implementation of a mandatory access control mechanism`

The basis is the model of mandatory access control `Bell–LaPadula`

The program operates as a `console application`

Providing a convenient `command line interface (CLI)` for performing basic operations

## 🧩 What modules are in the program?

  1. A module for `registration` and `authorization` of subjects

  2. A unique `object identification` module

  3. Methods that allow `subjects` to perform `object` operations

  4. An `administrator` module has been created in which subjects, objects and rights are managed

  5. A module to check the access right that wants to get a subject to an object in `real time`

  6. A `event audit` module that logging: events, failed accesses and successful operations
     
<p></p>
<div align="center">
  <img alt="Log" src="/Src/log.png" />
  <img alt="Help" src="/Src/help.png" />
</div>
<p></p>

## 🛠 Getting Started and Installation

Clone this repository. You will need to install `.NET SDK` and `Git` globally on your machine
<p></p>

1. Clone repository: `git clone https://github.com/HERN1k/Mandatory-Access-Control.git`

2. Go to the project folder:
   ```bash
   cd Mandatory-Access-Control
   
3. Installation dependencies:
   ```bash
   dotnet restore
   dotnet build

4. End you can run: 
   ```bash
   dotnet run
