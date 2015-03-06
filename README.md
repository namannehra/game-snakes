game-snakes
============

Web component providing a basic configurable snakes game. Use use arrow keys or 'a', 's', 'w', 'd' or touch screen to move. Use Space bar or Esc to pause/resume.

See the [component page](https://namannehra.github.io/game-snakes/) for more information.

## Getting Started

Import the element inside ```<head>``` tag:
```
<link rel="import" href="../game-snakes/game-snakes.html">
```

Put ```<game-snakes>``` tag inside ```<body>``` tag:
```
<game-snakes></game-snakes>
```

## Configuring the element (optional)

#### Configuring size, height, width, and time (optional)
Use attributes:
```
<game-snakes size="40" height="10" width="10" time="60"></game-snakes>
```

#### Configuring styling (optional)
Use CSS:
```
game-snakes {
	background-color: #4A148C;
}

/*styling food*/
game-snakes::shadow #food {
	border-radius: 2px;
	box-shadow: none;
}

/*styling snake's head and tail*/
game-snakes::shadow .tail, game-snakes::shadow #head {
	background-color: transparent;
	background-image: url('../game-snakes/hexagon.png');
	background-repeat: no-repeat;
	background-size: contain;
	box-shadow: none;
}
```

See the [component page](https://namannehra.github.io/game-snakes/) for more information.
