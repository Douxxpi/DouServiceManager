# 🧰 DouServiceManager

DSM is a tool for creating / removing services files on your debian based machine

## 📀 Requirements

To work properly, DouServer requires:

**Bases:**
- [node js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/package/npm)

**Packages:**
- [Yargs](https://yargs.js.org/)
- [Colors](https://www.npmjs.com/package/colors)

*note: all these packages are on [npmjs.org](https://npmjs.com) and can be installed with the command `npm install xyz` (xyz is the package name)*

## 🖥 Installation
To install DSM, follow these easy steps:
1. Make sure that you have [node js](https://nodejs.org/en) and [npm](https://www.npmjs.com/package/npm) installed on your device
2. open a terminal
3. copy and paste this command in the terminal:
```
curl -sSL https://douxx.xyz/dsm/install.sh | bash
```
If there is an error, you can install DSM step by step:
```
sudo git clone https://github.com/douxxpi/DouServiceManager.git
cd DouServiceManager/
sudo npm install yargs colors
sudo chmod +x cmd.js
sudo npm link
```
4. DSM is now installed, you can now run it with
```
dsm
```

## ⚡️ Running DSM

You can run DSM from anywhere in your debian system using the following command:
```
dsm
```

This command will show an help table. You can use different options after the command:

`add`: for adding a new service 
`remove`: for removing an existant service

`add` has 2 arguments: `-c "<command>"` (the command that will be runned in the service) witch is required and `-n <service name>` (the name of the service)
`remove` has 1 argument: `-n <service name>` (the name of the service that you want to remove)


