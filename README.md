# APEX Flip CountDown Item Plugin
This jQuery based item plugin can act as a clock, countdown timer or counter.

##Demo
[APEX Flip CountDown Item Plugin - Click Here](https://apex.oracle.com/pls/apex/f?p=9468:8)

##Installation
Just import the 
```html
item_type_plugin_com_farzad_apex_flip_count.sql
```
file into your application.

Choose this plugin as your item type and change the settings to get the desired result.

For more documentation visit this link : [APEX Flip CountDown Item Plugin - Click Here](http://farzadsoltani.com/2017/03/14/timers-oracle-apex-retro-style/)

## Usage

Counter Mode:
```html
When set to ‘Yes’, all options other than Size and Start From become disabled.
You can choose a number for the counter to start from, or simply leave it empty for it to start from 1.
When this option is set to ‘No’ the counter mode is disabled and you get a simple clock displayed.
```


Size:
```html
The Size option is always visible. When in Counter, Clock or Countdown mode and 
sets the size of the Retro Flip Countdown timers. 
The available options are Large, Medium, Small and Extra Small.
```

Show Hour / Minute / Second:
```html
Setting any combination of these changes the visuals of the clock. 
If all of them are set to No you get nothing. 
Setting them all to yes displays the hour, minute and second of the current time. 
Note that these options only work in the clock mode, 
and not in the counter and countdown modes.
```

Time Format:
```html
When displaying a clock you can choose between a 12 or 24 hour time format.
```

Count to Date?:
```html
This is what actually sets the plugin on countdown mode. 
You can choose from a certain date and time in the future and the timers 
will start counting down to the given time. 
It’s a good option to show a timer for when a specific offer will end. 
A space between the date and time is absolutely necessary. A valid format is :

M/DD/YYYY HH:MM:SS

For example : 4/21/2017 18:46:23
```

Date:
```html
When Count to Date is set to ‘Yes’ this text field becomes visible and this 
is the date you set for the countdown timers to count to.
```


## Author

[Farzad Soltani - Github](https://github.com/farzadso)

[Farzad Soltani - My Website](http://www.farzadsoltani.com/blog)
