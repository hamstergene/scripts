Run command when any file in a folder changes
----

This simple script will execute a command whenever any file under the current folder is modified.

Use as poor man's continuous integration when experimenting with simple throwaway programs:

    $ run-on-change -c 'c++ main.cpp && ./a.out'
    
    $ run-on-change -c 'cargo build && cargo test'
    
    $ run-on-change -c './main.py'

Can be installed via Homebrew:

    $ brew install hamstergene/tap/run-on-change

