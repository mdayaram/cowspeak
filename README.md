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


### Usage

``` bash
$> cowspeak "Fabricator fabricator, yon pantaloons are aflame" 
$> fortune | cowspeak
```


### Future Work

* Be able to parse all flags that cowsay uses and pass them along.
* Add a -r flag to trigger the random cowfile picking, otherwise default to cow.


### Misc

Check out [Brian's version](https://github.com/bkendzior/briangle-bashrc/blob/master/.bashrc#L86) which was the start of this guy.

Also, for more cowfile fun, check out [Brian's cowfile](https://github.com/bkendzior/cowfiles) repo.
