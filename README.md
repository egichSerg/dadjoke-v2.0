# dadjoke-v2.0
Script (and dataset with jokes) for linux to write random dad jokes. 
Dataset (jokes.txt) can be expanded by adding more lines and script will write them too!

## Installation

Run the following commands in your terminal:

```
sudo curl "https://raw.githubusercontent.com/egichSerg/dadjoke-v2.0/main/jokes.txt" --create-dirs -o ~/Documents/jokes.txt
```
```
sudo curl "https://raw.githubusercontent.com/egichSerg/dadjoke-v2.0/main/dadjoke" -o /usr/local/bin/dadjoke && sudo chmod +x ${_}
```

## Usage
Just enter 
```
dadjoke
```
in your terminal and that's it!

## Important note
This is a fork of original 'dadjoke-cli' from [Anupya](https://github.com/Anupya/dadjoke-cli)
