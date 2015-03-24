# Babydebugger

This gem will comment-out/uncomment each line in your current working directory, including any subdirectories that contains the Javascript line  `debugger`. This gem will simply place a `//` infront of debugger to comment it out. You can also undo the previously commented d`debugger` by running `babydebugger -u` in your command prompt. 
If you invoke `babydebugger -r`, **it will remove the entire line containing a `debugger` breakpoint**!
You can invoke `-h` for a quick rundown of the options.
## Installation

 `gem install babydebugger`


At the moment, babydebugger will only work with the files that end in `.js` 

## Todo

-search for any file type and comment out debugger where ever it is.


**Credit**
--This gem was based on the <a href="https://github.com/danvisintainer/prybaby">Prybaby gem</a> made by <3 by <a href="https://github.com/danvisintainer">Dan Visintainer</a>
