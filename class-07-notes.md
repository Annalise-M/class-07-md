##  Reading Notes / cheat sheet
HTML book:

    Chapter 6: “Tables” (pp.126-145)

JavaScript Book:

    Chapter 3: “Functions, Methods, and Objects” (pp.106-144)

### Tables
what's a table | pg. 130

basic table structure | pg. 131

    <table>
    <tr>
    <td>

table headings | pg. 132

    <th>

spanning columns | pg. 133

spanning rows | pg. 134

long tables | pg. 135

    <thead>
    <tbody>
    <tfoot>

old code: width & spacing | pg. 137

old code: border & background | pg. 138

___

### JavaScript

creating an object | pg. 106

updating an object | pg. 107

creating many objects constructor notation | pg. 108

creaing objects using constructor syntax | pg. 110

create & access objects constructor notation | pg. 111

adding and removing properties | pg. 112

recap: ways to create objects | pg. 113

This (it is a keyword) | pg. 114

recap: storing data | pg. 116

arrays are objects | pg. 118

arrays of objects & objects in arrays | pg. 119

what are built-in objects? | pg. 120

three groups of built-in objects | pg. 122

* the browser object model: the window object | pg. 124

* using the browser object model | pg. 125

* the document object model: the document object | pg. 126

using the document object | pg. 127

* global objects: string object | pg. 128

working with string | pg. 130

* data types revisited | pg. 131

global objects: number objects | pg. 132

    isNan() | checks if the value is not a number
    toFixed() | rounds to specified number of decimal places - returns a string
    toPrecision() | rounds to total number of places - returns a string
    toExponential() | returns a string representing the number in exponential notation

working with decimal numbers | pg. 133

global objects: math object  | pg. 134

    Property | Description
    Math.PI | returns pi - approximately 3.14159265359

    Method | Description
    Math.round() | rounds number to the nearest integer
    Math.sqrt(n) | returns square root of positive number, e.g., Math.sqrt(9) returns3
    Math.cell() | rounds number up to the nearest integer
    Math.floor() | rounds number down to the nearest integer
    Math.random() | generates a random number between 0 -inclusive- and 1 -not inclusive-

math object to create random numbers | pg. 135

creating an instance of the date object | pg. 136

global objects: date object -and time- | pg. 137

    Method | Description
    getDate() / setDate() | returns/ sets the day of the month 1-31
    getDay() | returns teh day of the week 0-6
    getFullYear() / setFullYear() | returns/ sets the year -4 digits-
    getHours() / setHours() | returns/ sets the hours
    getMilliseconds() / setMilliseconds() | returns/ sets the milliseconds 0-999
    getMinutes() / setMinutes() | returns/ sets minutes 0-59
    getMonth() / setMonth() | returns/ sets month 0-11
    getSeconds() / getSeconds() | returns/ sets seconds 0-59
    getTime() / setTime() | number of milliseconds since January 1, 1970, 00:00:00 UTC -coordinated universal time- and a negative number for any time before
    getTimezoneOffset() | returns time zone offset in mins for locale
    toDateString() | returns 'date' as a human-readable string
    toTimeString() | returns 'time' as a human-readable string
    toString() | returns a string representing the specified date

creating a date object | pg. 138

working with dates & times | pg. 139


