# Solidity-examples
This is a repository to get started with solidity

## Get Busy!

Click the link bellow to opone this repository on Gitpod.

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/gbarros/solidity-examples)

## How to 

How to reproduce the initial "empty" state of this repo? 
    You just need to follow these steps: 

> yarn init
 
fill in the info you'd like to have here

Now let's add the hardhat tool


> yarn add --dev hardhat

Let's create a boilerplate hardhat project for TS, run:

> npx hardhat

Add a very useful missing plugin on the boiler plate:

>  yarn add --dev hardhat-deploy

and add it to your `hardhat.config.ts`

```ts
import "hardhat-deploy"
```

You are going to notice that "deploy" option was added to the hardhat options.

Now you are good to go!



## Tips

I encourage you to add these extensions to your .gitpod.yml

 - dbaeumer.vscode-eslint
 - NomicFoundation.hardhat-solidity