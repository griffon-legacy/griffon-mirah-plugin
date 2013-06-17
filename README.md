
Brings the Mirah language compiler and libraries
------------------------------------------------

Plugin page: [http://artifacts.griffon-framework.org/plugin/mirah](http://artifacts.griffon-framework.org/plugin/mirah)


The Mirah plugin enables compiling and running [Mirah][1] code on your Griffon application.

Usage
-----
You must place all Mirah code under `$appdir/src/mirah`, it will be compiled first before any sources available on 
`griffon-app` or `src/main` which means you can't reference any of those sources from your Mirah code, while the
Groovy sources can.


[1]: http://www.mirah.org
[2]: /plugin/lang-bridge

