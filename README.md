# pgt &nbsp; ![DEVELOPMENT STATUS: completed](https://badgen.net/badge/DEVELOPMENT%20STATUS/completed/green)
<b>p</b>refixes for <b>g</b>i<b>t</b>

Your commit messages' prefixes.
<hr>

You keep forgetting what prefix to use for what commit?
> `Feat`, `Add`? What should I use? Can I even use `New`??

Does that sound like you sometimes? Not anymore!
This python script keeps a list of all your commit messages' prefixes. You can see all of
them or search for one. The top search result is automatically copied. 😊

## Example:
You are working on your project and you just added a new functionality, but forgot what prefix is the
appropriate one to use. You could see a list of all the known prefixes and use the one you deem fit, like so:
```console
$ pgt
```
Or you could search for prefixes with terms that best describe your commit changes, for example:
```console
$ pgt new feature
```

## How-to:
1. Put the [**pgt**](pgt) script with your other **bin**aries, or in a separate folder, but then don't forget
to include that folder to your **PATH** variable (There are plenty of resources out there if you don't know how to do the latter)
3. Add execution rights to it: ```$ chmod u+x pgt```
4. Rehash to use instantly: ```$ rehash```

## Requirments:
- `python 3.10` or greater
- `pyperclip` module if you want the copying functionality
