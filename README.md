For this project, Manjaro Linux was used, which is a linux distribution derived from archlinux.

For de install and start de proyect it is recomended  to use a VPN

## Installing Enviroment

###### Manjaro Linux

> First, install nodejs in the LTS version  18.13.0 which is one of the last, for this I use [nvm](https://github.com/nvm-sh/nvm#manual-install)

> Second, install [truffle](https://trufflesuite.com/docs/truffle/how-to/install/) in the last version what is available in [Truffle Suit](https://trufflesuite.com/), to create compile and deploy smart contracts on the blockchain.
>
> Third, install [ganche](https://trufflesuite.com/ganache/) in the last version what is available in [Truffle Suit](https://trufflesuite.com/) , to start a personal Ethereum blockchain that you can use to run tests, execute commands, and inspect state while monitoring how the chain works.
>
> Fourth, install [react](https://es.reactjs.org/) to creat the frontend for this web aplication
>
> ```
> sudo npm install -g create-react-app
> ```

###### Windows

First, install nodejs in the LTS version  18.13.0

1. Dowload [Nodejs v 18.13.0](https://nodejs.org/es/download/releases/)
2. Execute the installer

Second, install [truffle](https://trufflesuite.com/docs/truffle/how-to/install/) in the last version what is available in [Truffle Suit](https://trufflesuite.com/), to create compile and deploy smart contracts on the blockchain.

Third, install [ganche](https://trufflesuite.com/ganache/) in the last version what is available in [Truffle Suit](https://trufflesuite.com/) , to start a personal Ethereum blockchain that you can use to run tests, execute commands, and inspect state while monitoring how the chain works.

Fourth, install [react](https://es.reactjs.org/) to creat the frontend for this web aplication

```
sudo npm install -g create-react-app
```

## Getting Started

First, download the node-module for this proyect, for this in the terminal

```
cd <rute-of the proyect>
npm install
```

Second, deploy Smart Contract:

1. In the proyect file open a terminal and put the command

   ```
   truffle compile
   ```
2. Deploy Ganache

* In Manajro Linux:

  ```
  cd <ruta de descarga de la imagen de ganache>
  chmod +x ganache-2.5.4-linux-x86_64.AppImage
  ./ganache-2.5.4-linux-x86_64.AppImage
  ```

  In the ganache descktop aplication create new workspace and setect de archive truffle-config.json what was generated when the contract was compiled and start de blockchain
* Windows:
  Open the ganache descktop aplication  and create new workspace and setect de archive truffle-config.json what was generated when the contract was compiled and start de blockchain

3. Deploy the Smart Contract
   In the terminal put the comand

   `truffle deploy`

Third, run the development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.
