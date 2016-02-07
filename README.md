google-map
==========

Forked from https://github.com/GoogleWebComponents/google-map

**Add China Support**

```
$ bower install gutenye/google-map#master
<google-map latitude="37.77493" longitude="-122.41942" library-url="http://maps.google.cn/maps/api/js?callback=%%callback%%&v=3.exp"></google-map>
```

also needs to change `google-apis/google-map-api.html`

Due to `You have included the Google Maps API multiple times on this page. This may cause unexpected errors.` problem, so can not use compute to watch libraryUrl changes.

