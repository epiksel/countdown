jQuery Countdown Clock
=========

jQuery countdown plugin that accounts for timezone.

#Usage

```JS
$('.countdown').countdown({
    date: '07/27/2015 17:00:00',
    offset: +2
}, function () {
    alert('Done!');
});
```

#Options
Option | Description
---|---
date | Target date, ex `07/27/2015 17:00:00`
offset | UTC Timezone offset

You can also append a callback function which is called when countdown finishes.
