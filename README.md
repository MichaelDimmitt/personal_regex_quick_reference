## personal_regex_quick_reference

Some rules that are helpful with regex:
```
^ - means enforce it matches the beginning.
$ - means enforce it matches the end.
? - means match characters excluding escaped characters and line breaks.
. - means matches a single character escaped characters and line breaks.
```

All of this information can be learned by looking at the regexr site.

My current process for resolving regular expresions: https://regexr.com/

```
Find all instances of class="" or class='' in an html file.
class=(["'])(?:(?=(\\?))\2.)*?\1
condensed further: 
class=(["'])(?:(?=(\\?)).)*?\1
```

This is a personal reference as I use them I will list further commands.
