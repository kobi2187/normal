# normal
Making haxing comfortable.
A more proper stdlib for haxe, reimplementing common std functions from various languages


Haxe std lib feels quite primitive to me. 
It's an ambitious project, especially for someone without much free time.
it'll probably be simple things like path.combine, filter, map, iota, simple utils that I came to expect.

higher level coding, compared to indexof and substrings... which are error prone and somewhat unproductive imo. 

## candidates:
   - csharp (which version?)
   - factor
   - elixir
    ---
   - fantom
   - ruby
   - rebol
    ---
   - go
   - swift
   - java
   - groovy
   - lua
   - python

...And a preferred api, where functions proxy to the implementation in one of those langs.
this is an api project. common code in one package will "proxy" to another package.
we only talk about the standard library, not everything else that builds upon it.
but it may also make it easier to port software, or ease newcomers.

it may also test Haxe's shortcomings or wanted features.