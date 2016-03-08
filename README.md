# Zork

[![Build Status](https://travis-ci.org/richelbilderbeek/Zork.svg?branch=master)](https://travis-ci.org/richelbilderbeek/Zork)

Zork made compilable by Qt Creator.

## Building

From the command-line:

```
./build.sh
```

From Qt Creator:

 * Start Qt Creator
 * Open `Zork.pro`
 * Press Run (it will run, but not work, see `It runs but it does not work!`)

## It runs but it does not work!

It does not work because of the following error:

```
I can't open /usr/games/lib/dunlib/dtextc.dat.
```

Solution: 

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
