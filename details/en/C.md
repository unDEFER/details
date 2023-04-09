# @CaseCommand

The case command in Bash allows you to compare a string with multiple values.
In this case, the same behavior when matching different strings
is provided by logical "OR" symbol `|`. And comparison with an arbitrary
string with asterisk `*`.

# @CheckEmptyString

The `[ -z "string" ]` construct is the same as `test -z "string"` command
and returns zero (success) if the string is empty.

`man test` for details on what other tests test can do.

# @CheckUtilities

Bash provides the basic functionality for creating script logic,
but other programs usually do the bulk of the work. We check existance of
the programs we need, because otherwise the script will still fall,
but with an ugly error.

# @ColorsInBash

You can use terminal control characters to make output in Bash colored.

So the sequence `\x1B[1;37m` switches the output color to bright white
(at least for a terminal with a dark color scheme, I did not check
the script in a white terminal).
And `\x1B[1;0m` switches the output color back.
