## Steps to enable contentctl
- Ensure venv
```
source venv/bin/activate
```

- Contentctl new parameters
```
contentctl new --path content --type detection --app.title Custom_detections --app.appid DA-ESS-Custom-detections --app.prefix CUS --app.label CUSLABEL
```

- Contentctl BUILD
```
contentctl build --path content --app.title Custom_detections --app.appid DA-ESS-Custom-detections --app.prefix CUS --app.label CUSLABEL


[CUSLABEL - Add or Set Windows Defender Exclusion - Rule]
action.correlationsearch.label = CUSLABEL - Add or Set Windows Defender Exclusion - Rule
Build of 'Custom_detections' APP successful to content/dist/DA-ESS-Custom-detections-latest.tar.gz

Custom_detections - no where else
```