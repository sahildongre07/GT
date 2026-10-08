 Game written in TypeScript and utilizes HTML's `canvas`. Player is playing against an AI that uses Minimax algorithm and alpha-beta pruning. The evaluation function is hard-coded, and hence the AI may not be moving using the most optimal move.
 

 

### Objective

_Connect four_ of your game pieces vertically, horizontally, or diagonally before the other player do so.

### How to move?

At each turn, player will drop a game piece in one of the seven columns by clicking on the chosen column.

### More info

Read [Wikipedia page on Connect Four](https://en.wikipedia.org/wiki/Connect_Four)

## Browser compatibility

Should be good in latest Firefox, Edge, Chrome, and Safari.

 

### Developing

 Install dependencies

```
yarn install
```

 Start local development server

```
yarn dev
```

. Make your changes at either `browser/`, `core/`, or `server/`
. Test it out at http://localhost:5173/
 
 
