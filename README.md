# Zork

Zork made compilable by Qt Creator.

## Building

 * Start Qt Creator
 * Open `Zork.pro`
 * Press Run (it will run, but not work)

## It runs but it does not work!

```
I can't open /usr/games/lib/dunlib/dtextc.dat.
```

Copy the file `dtextc.dat` to the same folder as the executable

## Errors

### `Cannot find -lcurses`

```
sudo apt-get install libncurses-dev
```

### `Cannot find -ltermcap`

```
sudo apt-get install libncurses-dev
```
