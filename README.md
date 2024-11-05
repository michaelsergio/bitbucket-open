# Bitbucket Open

Opens files in bitbucket or prints the bitbucket URL from a git repo

## Usage:

`bitbucket -n ` - Prints URL to bitbucket repo for the branch you are in.

`bitbucket -n file` - Prints URL to bitbucket repo.

`bitbucket ` - Automaticlly opens the bitbucket repo for the branch you are in.

`bitbucket file ` - Automaticlly opens the bitbucket repo to the file.


## Installation: 

Add the following to your shell scripts:

`alias bitbucket="path-to-this-file/bitbucket-open/bitbucket"`

Make sure the file is executable

## Development 

Use shellcheck to validate the shell file
