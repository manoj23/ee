# ee

*ee* is a wrapper of *dd* that makes it safer to use.

It prints a warning when:
* the file given to *of* is not a block device
* the file given to *of* is a non-removable device

### bash completion with ee?

To get the same completion as *dd*, put in your `.bashrc` the following
lines:
```
_completion_loader dd
complete -F _dd -o nospace ee
```
