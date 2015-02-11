game-snakes
============

See the [component page](http://namannehra.github.io/game-snakes/) for more information.

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
<game-snakes size="20" height="15" width="25" time="60" instructions="The regular snakes game"></game-snakes>
```

#### Configuring styling (optional)
Use CSS:
```
game-snakes {
	background-color: #4A148C;
}

/*styling play button*/
game-snakes::shadow #playButton {
	background-color: #7B1FA2;
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

/*styling the overlay behind play button*/
game-snakes::shadow #overlay {
	background-color: rgba(255,255,255,0.54);
}
```

See the [component page](http://namannehra.github.io/game-snakes/) for more information.
