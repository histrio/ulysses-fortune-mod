# Ulysses Fortune-Mod

A custom [fortune-mod](https://en.wikipedia.org/wiki/Fortune_(Unix)) database containing quotes from *Ulysses* by James Joyce.
This repository includes a selection of quotes from the novel, complete with attribution to characters and context,
to add some literary flair to your terminal.

## Overview

The fortune-mod package displays random quotes when run from the command line. This repository adds a custom database 
with quotes from *Ulysses* by James Joyce, bringing you philosophical, witty, and reflective snippets from the novel
every time you run `fortune`.

## Installation

### Prerequisites

Make sure you have `fortune-mod` installed on your system.

### Setting Up the Ulysses Fortune Database

1. Clone this repository to your local machine:
```bash
git clone https://github.com/histrio/ulysses-fortune-mod.git
cd ulysses-fortune-mod
``` 

2. Copy the `ulysses` file to the fortune-mod directory:
```bash 
sudo cp ulysses ulysses.dat /usr/share/games/fortunes/
```

3. Verify that the database has been installed by running
```bash
fortune ulysses
```

You should see a random quote from Ulysses displayed in your terminal.

## Usage

Once installed, you can display a random Ulysses quote by running:
```bash
fortune ulysses
```

To include Ulysses quotes alongside your regular fortunes, simply run:
```bash
fortune
```

You can also add this to your shell startup file (e.g., `.bashrc` or `.zshrc`) 
so that you see a quote every time you open a terminal session:

```bash
echo 'fortune ulysses' >> ~/.bashrc
source ~/.bashrc
```

## License

This project is licensed under the MIT License. See the LICENSE file for details.
