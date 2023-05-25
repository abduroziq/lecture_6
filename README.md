# DATA AND TIME
 In this tutorial, you will learn about date and
time in JavaScript with the help of examples.
>In JavaScript, date and time are represented by the Date object. The Date object
provides the date and time information and also provides various methods.
A JavaScript date defines the EcmaScript epoch that represents milliseconds
since 1 January 1970 UTC. This date and time is the same as the UNIX epoch
(predominant base value for computer-recorded date and time values).
There are many ways to format a date as a string. The JavaScript specification only specifies one format to be universally supported: the date time string format, a simplification of the ISO 8601 calendar date extended format. The format is as follows:

# Creating Date Objects
There are four ways to create a date object.
•new Date()
•new Date(milliseconds)
•new Date(Date string)
•new Date(year, month, day, hours, minutes, seconds,
milliseconds)
# new date
You can create a date object using the new Date() constructor. For example,
new Date(year, month,...) creates a new date object with the specified date
and time.
>const d = new Date();

# new Date(milliseconds)
>A Date object contains a number representing milliseconds
since January 1, 1970 UTC. New Date(milliseconds) Creates a
new Date object by adding milliseconds to the zero time. For
example,

# new Date (date string)
>
Short and Long date format
New Date - (date string) creates a new date object from the date string.In JavaScript, there
are generally three date input formats. ISO Date Formats You can create a date object by
passing ISO date formats.

Note: If you pass only one argument, it  will count as milliseconds.
Therefore, to use this date format, you must pass two arguments. In
JavaScript, months are counted from 0 to 11. January is 0 and
December is 11.

# DATE METHODS
 # now()
Date.now() returns the number of milliseconds since January 1, 1970.
# getFullYear()
getFullYear() returns the full year of a date (4 digits).

# getMonth()
getMonth() returns the month (0 to 11) of the date. January = 0, February = 1, ..
# getDate()
The getDate() method returns the day of the month (1 to 31) of the date.
# getDay()
The getDay() method returns the day of the week (0 to 6) of the date. Sunday = 0, Monday = 1, 
# getHours()
getHours() returns the hours (0 to 23) of a date.

# getMinutes
getMinutes() returns the minutes (0 to 59) of a date.
# getUTCDate()

getUTCDate() returns the day of the month (1 to 31) of a date object.
getUTCDate() returns the date in UTC.
# setFullYear()
getUTCDate() returns the day of the month (1 to 31) of a date object.
getUTCDate() returns the date in UTC.

# setFullYear()
The setMonth() method sets the month of the date object.
This method can also be used to set the day of the month

# lecture_6
