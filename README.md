# CodeServe: Simple source browser
CodeServe is a simple server that will serve beautiful looking source code.
## Features
- Syntax highlighting
  - Uses vim syntax highlighter
  - Change vim colorscheme client side and server side
- Browse directories
- Link include files in C/C++

## How to Use
Run CodeServe with:

    code_serve.py

To see options run:

    code_serve.py --help

## See it in Action
I have an instance of CodeServe serving the Box2D code here: [Box2D - CodeServe](http://vader.co:8080/Box2D/)

I used the command:

    code_serve.py -p 8080 -v 'colorscheme delek' 'set bg=dark' -i /usr/include/ /usr/include/c++/4.7.2/

## Requirements
CodeServe requires

- vim
- Python 2.7
- memcached
- python2-memcached

## Author
[Clark DuVall](http://clarkduvall.com)
