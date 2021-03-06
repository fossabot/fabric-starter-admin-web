# Web application for Hyperledger Fabric decentralized application 
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Folegabu%2Ffabric-starter-admin-web.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2Folegabu%2Ffabric-starter-admin-web?ref=badge_shield)


Starter application built with [Aurelia](https://aurelia.io/) to connect to 
[REST API servers](https://github.com/olegabu/fabric-starter-rest) and transact on 
[Hyperledger Fabric](https://www.hyperledger.org/projects/fabric) blockchain network
created with [Fabric Starter](https://github.com/olegabu/fabric-starter).

## Install and build

Install prerequisites: Node.js. This example is for Ubuntu 18:
```bash
sudo apt install nodejs npm
```

Install Aurelia CLI
```bash
sudo npm install aurelia-cli -g
```

Build
```bash
npm install && au build --env prod
```
## Create and start the network

Follow instructions on  [Fabric Starter](https://github.com/olegabu/fabric-starter) to create a network of member 
organizations who will run their REST API servers which will serve this web app.

- org1 [http://localhost:4000/webapp/](http://localhost:4000/webapp/)
- org2 [http://localhost:4001webapp/](http://localhost:4001/webapp/)

## Development

Run in development
```bash
au run --watch
```
Your web application served by `au run` in development at [http://localhost:9000](http://localhost:9000) will connect
to the API server of org *a* [http://localhost:3000](http://localhost:3000).





## License
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Folegabu%2Ffabric-starter-admin-web.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2Folegabu%2Ffabric-starter-admin-web?ref=badge_large)