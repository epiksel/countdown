jQuery Countdown Clock
=========

jQuery countdown plugin that accounts for timezone.

[DEMO PAGE](https://epiksel.github.io/countdown/demo) | [OPENCART EXTENSION](https://openix.io/en/product/preview?pid=57)

# Usage

```javascript
$('.countdown').countdown({
    date: '07/27/2015 17:00:00',
    offset: +2,
    day: 'Day',
    days: 'Days',
    hideOnComplete: true
}, function (container) {
    alert('Done!');
});
```

# Options
Option | Description
---|---
date | Target date, ex `07/27/2015 17:00:00`
offset | UTC Timezone offset
day | a Day text
days | an Days text
hour | a Hour text
hours | an Hours text
minute | a Minute text
minutes | an Minutes text
second | a Seccond text
seconds | an Seconds text
hideOnComplete | hide container when countdown is 0 (Default=false)

You can also append a callback function which is called when countdown finishes.
