# jquery-countdown-timer


```
$('#countdown1').countdownTimer('2019/11/12 12:00', function() { console.log('end'); });
$('#countdown2').countdownTimer('2019/11/12 12:00')
    .on('countdownTimer:end', function() { console.log('end'); })
$('.countdown').countdownTimer('2019/11/12 12:00', function() { console.log('end'); });
```

```
<div class="#countdown1">{day}days{hour}:{min}:{sec}.{ms}<div>
<div class="#countdown2">{day:00}days{hour:00}:{min:00}:{sec:00}.{ms:00}<div>


<div class="countdown">{day}days{hour:00}:{min:00}:{sec:00}.{ms:00}<div>
<div class="countdown">{hour:00}:{min:00}:{sec:00}.{ms:00}<div>
<div class="countdown">{min:00}:{sec:00}.{ms:00}<div>
<div class="countdown">{sec:00}.{ms:00}<div>


<div class="countdown">{day:00}days{hour:00}:{min:00}:{sec:00}<div>
<div class="countdown">{day:00}days{hour:00}:{min:00}:{sec:00}.{ms:0}<div>
<div class="countdown">{day:00}days{hour:00}:{min:00}:{sec:00}.{ms:00}<div>
<div class="countdown">{day:00}days{hour:00}:{min:00}:{sec:00}.{ms:000}<div>


```

```
$('div').countdownTimer('2019/11/12 12:00', function() { $('#xxx').xxx(); });
```
