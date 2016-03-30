# normal

Making haxing comfortable.
A more proper stdlib for haxe, reimplementing common std functions from various languages


Haxe std lib feels quite primitive to me, so this is a semi-baked attempt to change that. 

It's an ambitious project, especially for someone without much free time.

BUT it'll probably be simple things like path.combine, filter, map, iota, simple utils that I came to expect.

Higher level coding, compared to indexof and substrings... which are error prone and somewhat unproductive imo. 
more passing data and structs around, than complex functions.
these are just static functions, possibly with data structures.

TODO: determine dependency within the stdlib. which functions are most built upon? +graphviz?

it should give some prioritization. also do easy things first, or ones that bring much convenience to coding.

## candidates

first those

- csharp (which version?)
- factor
- elixir

then maybe

- fantom
- ruby
- rebol

i don't know yet how big those are

- go
- swift
- java
- groovy
- lua
- python

document or file a bug report, when it's impossible or needs crazy workarounds to implement in Haxe.

...And a preferred api, where functions proxy to the implementation in one of those langs.
this is an api project. common code in one package will "proxy" to another package.
we only talk about the standard library, not everything else that builds upon it.
but it may also make it easier to port software, or ease newcomers.

it may also test Haxe's shortcomings or wanted features.