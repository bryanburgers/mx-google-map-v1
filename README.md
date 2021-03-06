# MX Google Map CE V1 #

_Note: This is a private fork which includes pull requests that have not yet been merged, but which we need. Please use the [original][mx] unless you specifically need these fixes._


[Documentation](http://www.eec.ms/add-ons/mx-google-map)

[Examples](http://www.demo-ee.com/examples/view/mx-google-map-hold-js)

![MX Google Map V1](images/mx-google-map-field__large.png)




## Using An API Key

If you use [Master Config][masterconfig], add the following to config.master.php:

```
$env_config['mx_google_map:api_key'] = 'YOUR_API_KEY';
```

`YOUR_API_KEY` can be retrieved at [https://code.google.com/apis/console](https://code.google.com/apis/console).


[mx]: https://github.com/MaxLazar/mx-google-map-v1
[masterconfig]: https://github.com/focuslabllc/ee-master-config
