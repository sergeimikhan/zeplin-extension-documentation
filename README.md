# Netco Zeplin extension 

## From the office.

To integrate:

1. Go to project where you want to integrate plugin
2. Go to menu "Extenstions" -> "Manage Extenstions..."
3. On Mac, holding down the `⌥ Option` key will enable the `Add Local Extension` option on the title bar:

![Add local extension](https://github.com/zeplin/zeplin-extension-documentation/blob/master/img/addLocalExtension.png?raw=true)

4. Put http://10.50.33.42:8081/manifest.json here and enjoy


## Run locally latest revision

0. install proper `node` version:

```sh
# install nvm
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.2/install.sh | bash

#install node
nvm install 8.9.4
```
1. clone this repo and run the following commands

```sh
npm install
npm start
```

2. add extension using this link `http://localhost:7070/manifest.json`
