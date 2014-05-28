vim-bdd
=======

Vim functions to run RSpec and Cucumber on the current cursor or file. It also supports Spork, Zeus and Spring.

Shortcuts:

 - `<Leader>;` - runs a spec example or feature under cursor
 - `<Leader>'` - runs the whole spec or feature file in current buffer

Spring
------

vim-bdd supports only globally installed Spring (e.g. `gem install spring`).

For [Spring](https://github.com/jonleighton/spring) support create
`~/spring.rb` file. The file can be empty.
