CowSpeak
========

Authors: [Manoj Dayaram](https://github.com/mdayaram), [Brian Kendzior](https://github.com/bkendzior)

Like cowsay, only that it speaks too!  Unfortunately, only supported in Linux and Mac OS X for ever.

### Dependencies:

 * cowsay
 * wc
 * espeak (linux)
 * say (darwin)
 * cat
 * getopt


### Usage

``` bash
$> cowspeak "Fabricator fabricator, yon pantaloons are aflame" 
$> fortune | cowspeak
$> cowspeak -r "This will choose a random cowfile"
$> cowspeak -t -f sheep "All cowsay command line flags are passed through appropriately"
```


### Misc

Check out [Brian's version](https://github.com/bkendzior/briangle-bashrc/blob/master/.bashrc#L86) which was the start of this guy.

Also, for more cowfile fun, check out [Brian's cowfile](https://github.com/bkendzior/cowfiles) repo.
