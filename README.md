## Tic-Tac-Toe
A basic tic-tac-toe game made using React to learn the basics of the framework.  
![next-next][third]

#### Dependencies  
1. nodejs 
2. npm (comes bundled with nodejs)
3. npx (comes bundled with npm 5.2+)  

Run the following commands on your bash terminal (Ubuntu 18.04) and you'll have installed all the dependencies:  

``` shell
curl -sL https://deb.nodesource.com/setup_12.x | sudo -E bash -
sudo apt-get install -y nodejs
```

#### How to start the game
Although I could've simply attached the script to a HTML page so that you can simply play the game on a page in your browser, I didn't and that's probably because you (a viewer) doesn't exist. But if you do, you're all *pros*, I know it.

After finishing the installation of dependencies, do the following steps:

``` shell
git clone 'this repo'
cd Tic-Tac-Toe-basic
npm start
```

In case of any errors, trying the following:
``` shell
cd Tic-Tac-Toe-basic
npx create-react-app xyz
//installs reacts and dependencies
rm -r xyz
npm start
```
##### Screenshots
![initial][first]
![next][second]

first: https://github.com/Damercy/Tic-Tac-Toe-basic/blob/master/screenshots/initial.png 'Initial Screen'
second: https://github.com/Damercy/Tic-Tac-Toe-basic/blob/master/screenshots/intermediate.png 'In-between Screen'
third: https://github.com/Damercy/Tic-Tac-Toe-basic/blob/master/screenshots/final.png 'Final Screen'
