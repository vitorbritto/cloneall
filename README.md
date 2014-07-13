![Cloneall Logo](src/cloneall.jpg "Cloneall")


## Welcome

Cloneall is a simple method to clone all repositories from a specific user or organization on GitHub.


## Installation

```bash
# 1. Clone this repository
$ git clone git://github.com/vitorbritto/cloneall.git

# 2. Place the `cloneall.sh` script wherever you want

# 3. Make the script executable
$ chmod u+x path/to/cloneall.sh
```


## Usage

```bash
# 1. Change the destination to clone repositories on VARIABLES section
dist="$HOME/Dropbox/Github"

# 2. Run the script on Shell
$ ./cloneall.sh [options] <username> <page number>

# 3. Edit the generated text file in user path to clone specific repositories
#    OR continue to clone all repositories from specific page
```

### Options:

```bash
    -h, --help        output help
    -c, -clone        clone repositories
```

## Bonus

If you prefer, put the following **alias** inside your `~./.bashrc` file:

    alias call="bash ~/path/to/script/cloneall.sh"

Now, you can simply run:

    $ call [options] <username> <page number>


## License

[MIT License](http://vitorbritto.mit-license.org/) © Vitor Britto
