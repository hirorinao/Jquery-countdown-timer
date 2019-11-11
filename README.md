# jquery-countdown-timer

## Demo

[Demo Countdown Timer](https://hirorinao.github.io/jquery-countdown-timer/demo.html)

## Download
[jquery.countdown-timer.js](https://github.com/hirorinao/jquery-countdown-timer/releases/download/v1.0/jquery.countdown-timer.min.js)

## Setup
```
<script type="text/javascript" charset="UTF-8" src="https://ajax.googleapis.com/ajax/libs/jquery/2.1.4/jquery.min.js"></script>
<script type="text/javascript" charset="UTF-8" src="js/jquery.countdown-timer.min.js"></script>
```

```
$('#countdown1').countdownTimer('2019/11/12 12:00', function() {
    console.log('end');
});

$('#countdown2').countdownTimer('2019/11/12 12:00')
.on('countdownTimer:end', function() { console.log('end'); })

$('.countdown').countdownTimer('2019/11/12 12:00', function() {
    console.log('end');
});
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
$('<dummy>').countdownTimer(Date.now() + 2000, () => console.log('2 seconds later'));
$('<dummy>').countdownTimer('2019/11/12 12:00', () => $('#content').css({display: 'none'}));
```

## Debug

```
http://xxxxxx.xxx/xxxxx?_countdown_now=20xx-xx-xx.xx:xx
```
