<a href="https://codeclimate.com/github/cyzanfar/babydebugger"><img src="https://codeclimate.com/github/cyzanfar/babydebugger/badges/gpa.svg" /></a>
[![Gem Version](https://badge.fury.io/rb/babydebugger.svg)](http://badge.fury.io/rb/babydebugger)

# Babydebugger

Comment out, uncomment or delete `debugger` breakpoints from JavaScript files ending with `.js`.

This program will execute on `.js` files in your current directory including any subdirectories.


## Installation

`gem install babydebugger`

At the moment, babydebugger only execute files ending in `.js`

## Usage
By default, running `babydebugger` will comment out debugger breakpoints.

For a quick rundown of the available options run `babydebugger -h`.

Invoke `-r` remove breakpoints in files.

`-u`  uncomment lines with debugger breakpoints.



## Todo

-Support `.coffeescript` extension.

##Contribute

Fork this repository, clone your fork, create a new branch and start contributing!
