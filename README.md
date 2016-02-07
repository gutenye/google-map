google-map
==========

Forked from https://github.com/GoogleWebComponents/google-map

**Add China Support**

```
$ bower install gutenye/google-map#master
<google-map latitude="37.77493" longitude="-122.41942"></google-map>
```

**Make it works in Angular**

need delete default language, version, ... value in `google-apis/google-map-api.html` so that `_computeUrl` only called once in lifetime.
