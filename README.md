# FullStackCatalog
Main repository for the FullStackCatalog project, structured with submodules to separate Frontend, Backend, and API Gateway. The goal is to build a complete catalog using modern full-stack development technologies.

![GitHub repo size](https://img.shields.io/github/repo-size/Matt-Alves07/FullStackCatalog)
![GitHub contributors](https://img.shields.io/github/contributors/Matt-Alves07/FullStackCatalog)
![GitHub stars](https://img.shields.io/github/stars/Matt-Alves07/FullStackCatalog?style=social)
![GitHub license](https://img.shields.io/github/license/Matt-Alves07/FullStackCatalog)

## 📌 About the project
The **FullStackCatalog** is a full-stack modular project, created to demonstrate the development of a complete catalog using modern technologies. The project is structured into three main submodules, each representing a different layer of the application:
- **Frontend**: Built with React, this submodule handles the client-side logic and user interface;
- **Backend**: Folder with the C# applications, created to handle the server-side logic and data storage;
- **API Gateway**: Submodule responsible for managing the API requests and responses, built with Net 8 and Ocelot

## 📂 Project's structure
FullStackCatalog/
&nbsp;&nbsp;├── FullStackCatalog-Frontend/ (React + Vite)
&nbsp;&nbsp;├── FullStackCatalog-Backend/ (C# API's)
&nbsp;&nbsp;├── FullStackCatalog-Gateway/ (C# + Ocelot)

## 🚀 Technologies used in this project
- **Frontend**: React, Vite, JavaScript
- **Backend**: C#, .NET Web API
- **API Gateway**: C#, Ocelot API Gateway

## 🔧 Instalation
### 1️⃣ Cloning the main repository and submodules
```sh
git clone --recurse-submodules https://github.com/Matt-Alves07/FullStackCatalog
```

### 2️⃣ Initializing the submodules
```sh
git submodule update --init --recursive
```

### 3️⃣ Configuring and running the backend
```sh
cd FullStackCatalog.Backend
dotnet restore
dotnet run
```

### 4️⃣ Configuring and running the frontend
```sh
cd FullStackCatalog.Frontend
npm install
npm run dev
```

## 📜 License
This project is under public domain, licensed under **The Unlicense**.
Fell free to use, modify and distribute this project as you see fit, but, please, don't forget to give me the credits for the original work.
You can see more about the license in the [LICENSE](LICENSE) file.

## 🛠 Created and maintained by [Matt-Alves07](https://github.com/Matt-Alves07)