# details

details is simple script to support detail documentation in actual state.

# Detail documentation

The idea of detail documentation of program code is that always easy to explain
what does function do, but to understand how it does it necessary
to know many details. "The devil is in the details."
So in the code we are writing description of functions
and make references to details like @Detail\_Name.
All details explained in the "details" directory.
We can reference to any detail several times.
We don't translate comments in the code, but we can
want to translate details to several languages.

# Examples

This project itself detailed documented.
It is tiny script, but to understand it you need
to know many bash features. And detailed documentation
allows to describe it all easy.
You will see more examples in this section in the future.

# Difference from literate programming

Literate programming is also method of program code documentation.
But it demands from enough complex tools and after that you can't
give your code to compiler directly. It is easy to drop leterate
documentation, but hard to start it for existing project. So there are
too small such projects.

Detail documentation is alternative which easy to start write at
any time of project lifetime and tools to support it is very easy.

# Usage

Try:

    $ bin/details details/en bin list
    $ bin/details details/en bin omitted
    $ bin/details details/en bin unused
