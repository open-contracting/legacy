# Static site copies of old Open Contracting Data Standard sites

These can be viewed online at https://open-contracting.github.io/legacy/

## How this was created

`1.*` versions downloaded from original Django site with:

```
wget -rkp --no-parent "http://ocds.opendataservices.coop/standard/" 2> debug.log 
```

`0.*` versions from https://github.com/open-contracting/standard-collaborator/tree/master/django/website/main/templates/main/legacy

Broken links etc. were then manually edited.
