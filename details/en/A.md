# @ArgumentsInBash

In Bash, accessing command line arguments is very easy.
Just write dollar sign and an argument number.

In this case, $0 is name of a script itself,

$1 is the first argument,

$2 is the second, and so on.

Like variables, when used without quotes, the string
in an argument with spaces is passed to the command as multiple arguments.
Usually, with rare exceptions, this is undesirable behavior,
which is why we frequently quote arguments and variables in this script.
