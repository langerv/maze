# maze
maze generator in Go

``` Go
/* Prim generator */
prim := Prim{Width:20, Height:20, Seed:int64(0)}
if _, err := prim.Generate(); err != nil {
	fmt.Println(prim.String())
}
 _______________________________________
|___   _|_____  |_____   _|_   _____   _|
|___   _|_________   _|  _|___|_____   _|
|_____   _|  _   _______   ___|_____   _|
|_____   _|_|___|_     _   _|  _|_   ___|
|_____   _|  _|_  |_|___|  _|_   ___    |
|___   _   _____|_   _|_   ___|_|___  |_|
|_  |_|_   ___| |_   _|    _|_____   _  |
|_____   _       _|  _|_|_   ___   _|_  |
|_________| |_|___  |_______|_   ___|_  |
|  _|  _    |_____     _____   ___  |  _|
| |___| |_|_|  _____|_|_   ___  |_  |___|
| |_   _     _|  ___   _   _|_   _|___  |
|  _   _|_|___| |___   _|_|  _   _  |___|
|___|_|  _____   _|    ___|___|  _|_   _|
|_   _  |___   ___|_|_|___   _____|_    |
|_____|   |  ___|    _     ___|  _   _|_|
|  _____|_| |___  |_|___|  _|  ___|___  |
|_|_     ___    |_|___   _|  _|_     _  |
|_   _|_|  ___|_|_____  |_____|___|_|_  |
|___|___________|___________|___________|

```
