# Move Reviews from Weekends and Holidays

Do you want to take a break from doing your Anki reviews without having them pile up on the weekends, holidays or a vacation? Or do you have specific days on the week when you're too busy to do the reviews? Then this add-on is the solution to your problem!

It works by re-scheduling the already scheduled cards anytime by moving them either before, or after the specified days. By default, the intervals never change by more than 10\%, or by 7 days in any case.

## Mobile and other addons

This add-on plays well with mobile versions of Anki (AnkiMobile/AnkiDroid), assuming that the user also uses the desktop version, as the 

The add-on does not directly impact the scheduler, but instead reschedules already schedules cards, so it should play well with addons that patch the scheduler (for example, load balancer), but this is untested.

## Images
Before using the add-on reschedule:
![Before](https://raw.githubusercontent.com/vasarmilan/AnkiWeekendsAndHolidays/master/static/before.png)

After:
![After](https://raw.githubusercontent.com/vasarmilan/AnkiWeekendsAndHolidays/master/static/after.png)
## Usage and configuration

By default, the add-on will free up the weekends and nothing else. However, this behaviour can be changed to move the reviews away from specific dates and/or any day of the week.

Config can be edited in the Tools -> Add-on(Ctrl+Shift+A) -> Move Reviews from Weekends and Holidays. *Make sure to restart Anki after editing the configuration*.

Once you've set the dates and days of the week that you want to free up, you can use the shortcut *Ctrl+Shift+r* (by default) to reschedule the cards.

## Bug reports and source code

The source code is accessible at: https://github.com/vasarmilan/AnkiWeekendsAndHolidays

Please submit bug reports here, if you encounter any problems. PRs are also welcome.
