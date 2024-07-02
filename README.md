# CustomMEOWtivator
Purpose of use:

This is a desktop app for time management. To put it more simply, this
app allows the user to create custom notifications/alarms which pop up
once the timer for one of them runs out.

Alarm configuration:

Each notification/alarm has a set structure*. It consists of:
-an image file;
-a music file;
-a string of displayed text.

*for further annotaton please refer to the 'Creating a new alarm/Editing an 
existing alarm' portion of this guide.

Main Screen

When the user logs into the app, themain screen displays a list of 
selectable alarms, buttons for editing and deleting list items, 
button for creatina a new alarm(marked with a '+' icon) and a 
localization toggle to change the language of the visual interface between 
EN-english and RU-russian languages.

Alarm list data storage method:
The list of alarms is written into a .XML file at the end of each session,
and subsequently read from at the start of the next one.

Creating a new alarm:
When the user uses the 'new alarm'(marked with a '+' icon) button,
a sub view will appear. The user can choose between 'templates'(not yet 
implemented) and 'custom' configuration for the alarm. Each element
of the alarm structure can be chosen from the file system of the PC or
left empty, in which case a default icon and message will be displayed
upon the timer running out, with no sound. The message displayed can be
input into the corresponding text field of the sub window. The date and 
time of the larm can be choosen from the calendar. The default datetime
is set as the current system datetime.

After confirming the alarm configuration, it will appear in the alarm list.

Editing an 
existing alarm:
The user can only choose to edit one lis item at a time. Once the list item 
has been selected and the 'edit' button pressed, the same sub window as while
making a new alarm will appear. The list item's customisation data is then read 
from the alarm list and displayed in the window. The user can change(customise)
the alarm components as they wish.


After confirming the alarm configuration, the alarm list will be updated with the
edited alarm configuration.


Turning the alarms on/off:
To turn on the alarm the user must check the box next to the alarm list
item. And vice versa. 

Alarm notification:
When the timer for an alarm runs out, it goes off, displaying a graphic with text 
underneath it and playing a music file with media player - on top of the current 
active window in the host system. 
To turn off the alarm after it has gone off, the user has to press any key or click
on the notification image.

Distribution:
Please do not distribute this product without it's owner's(my) permission. This piece
of software is protected by copyright law and is not intended for commercial use.



