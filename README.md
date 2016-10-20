# hop

Run a command from another directory

e.g.
```
me@comp:~/mydir$ hop .. cp thing mydir
me@comp:~/mydir$ ls
thing
me@comp:~/mydir$
```

```
me@comp:~/repo1$ hop ../repo2 git commit -am 'Forgot to change something' && git push
```

## why

Jumping around directories is really annoying sometimes.

Inspired by `dip` from the [Factor](https://github.com/factor/factor)
programming language.

