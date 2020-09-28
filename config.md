## Configuration

###weekdays_skip[list of integers]
<b>Values:</b> "0=Mon, 1=Tue, 2=Wed, 3=Thu, 4=Fri, 5=Sat, 6=Sun"
<b>Default:</b> [5, 6]"
Reschedule cards scheduled on the days specified here.

###dates [string]
<b>Values:</b> "YYYY-MM-DD"
<b>Default:</b> ["1970-01-01"]
<b>Example:</b> ["2020-12-01", "2020-12-02", "2020-12-03"]

###Shortcut [string]
<b>Values:</b> Should be a valid shortcut string (QT), or empty ('')
<b>Default:</b> "Ctrl+Shift+r"

###Execute at startup [boolean as 0/1]
<b>Values:</b> 0 represents False, 1 represents True.
<b>Default:</b> 0

If set to 1, the rescheduling will always be executed at the startup of Anki, so it's not necessary to run it manually.

###max_change_percent [positive integer]
<b>Values:</b> 1-100 Positive Integer
<b>Default:</b> 10

Intervals won't be changed more than {max_change_percent}%.
Example: with the default value 10, a card with an interval of 100 could be rescheduled to have an interval no shorter, than 90 days, and no longer, than 110 days.

###max_change_days [positive Integer]
<b>Default:</b> 7

Intervals won't be changed by more, than the amount 

###max_days_lookahead [positive integer]
<b>Values:</b> 1-365 Positive Integer
<b>Default:</b> 365

Maximum lookup days - nothing will be rescheduled at any day later than (today + {max_days}).
Safe to leave at default value.
