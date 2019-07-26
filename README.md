# AWS assume role

This script can be used to assume role for AWS

## Usage

There are two ways how to use the script:

1. Execute directly
2. Source it

In the first case, you would run it like this:

```bash
./assume-role development
```

This will print out the tokens to the `stdout`

The second case will directly export the tokens to your current shell:

```bash
source ./assume-role development
```

You may want to create an alias for the `source`. It may be accomplished like this:

* Copy the script to some path for binnaries like ~/.local/bin/
* Edit your ~/.bashrc and insert `alias assume-role='source ~/.local/bin/assume-role'`
* Run `source ~/.bashrc`

You can also run the script without arguments in which case it will print some help.

