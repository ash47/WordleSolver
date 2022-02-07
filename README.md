# WordleSolver
Solves Wordle cause i'm bad at games :(

# How to get the answer?
 - You can get the answer instantly with the following JavaScript payload:
 ```JSON.parse(localStorage.getItem('gameState')).solution````
 
> (e.g. press F12 and paste this into your console)

# Can I use this on a mobile browser?
 - Bookmark the following and then just open the bookmark on mobile:

```
javascript://window.alert(JSON.parse(localStorage.getItem('gameState')).solution)
```