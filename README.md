# Static site copies of old Open Contracting Data Standard sites

If GitHub Pages is enabled, these can be viewed online at:

* https://open-contracting.github.io/legacy/r/1__0__0/en/
* https://open-contracting.github.io/legacy/r/1__0__0/es/
* https://open-contracting.github.io/legacy/r/1__0__RC/en/
* https://open-contracting.github.io/legacy/r/1__0__RC/es/
* https://open-contracting.github.io/legacy/r/0__3__3/
* https://open-contracting.github.io/legacy/r/0__3__2/
* https://open-contracting.github.io/legacy/r/0__2__0/
* https://open-contracting.github.io/legacy/r/0__1__0/

## How this was created

`1.*` versions downloaded from original Django site with:

```
wget -rkp --no-parent "http://ocds.opendataservices.coop/standard/" 2> debug.log 
```

`0.*` versions from https://github.com/open-contracting/standard-collaborator/tree/master/django/website/main/templates/main/legacy

Broken links etc. were then manually edited.
