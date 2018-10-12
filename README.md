# zero-time-picker
Time picker for MIT App Inventor 2 with automatic addition of "0" to hour or minute smaller than 10.

This sample MIT App Inventor 2 project nicely displays the selected time over the time picker button. It can be easily ported to displaying the time in a label or any other visual object.

The code adds a leading 0 (zero) to hours and minutes smaller than 10. For example, selecting 9:05 in the time picker will display the time as "09:05". Natively, App Inventor does not add leading zeros in such cases, so if you simply use timepicker.hour or timepicker.minute, you will get only be shown a single digit.

You can easily change the code to add a leading zero only to the minute and not to the hour, if you prefer 09:05 to be displayed as "9:05".

Installation instructions:
1. Download ZeroTimePicker.aia.
2. In App Inventor, go to Projects > Import Project (.aia) from my computer.
3. Select the downloaded file.
4. Voilà!
