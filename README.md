# adventure-game
Text-based adventure game for funsies

## Setup
* Download [nodejs](https://nodejs.org/en/download/), which will be used to run the game
* Use your favorite text editor. Maybe [VSCode](https://code.visualstudio.com/download)

### Install dependencies
* Install Typescript globally, which will allow your computer to compile your Typescript code. Use the command below to install it and then check your version:

```bash
npm install --global typescript | tsc --version
```

* Make sure you have [git](https://gitforwindows.org/), which will be used to add/edit code in this repository
You can check what version (if any) you have by using:

```bash
git --version
```

### From scratch
* Open the project folder in VSCode and create your Typescript file (maybe main.ts, game.ts, or whatever you want)
* Put in something simple, like below, and then save the file:
```typescript
console.log(`Testing, testing...`);
```
* Run the game with the command below, which will compile it into javascript first, and then use node to run the javascript:
```bash
tsc main.ts | node main.js
```
* note: just substitute <your-file-name>.ts and <your-file-name>.js in the above command.
