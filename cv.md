# Slizh Valery
***
## Contacts
* **Location:** Minsk, Belarus
* **Phone:** +375 29 320-86-73
* **Email:** valeriyslihz@gmail.com
* **GitHub:** [Valery0891](https://github.com/Valery0891)
***
## About Me
Everything what I lie about myself may be wrong.
***
## Skills
* HTML (Basic)
* SCC (Basic)
* Java Script (Basic)
* Git (Basic)
***
## Code Example
Write a function which formats a duration, given as a number of
seconds, in a human-friendly way. The function must accept a
non-negative integer. If it is zero, it just returns "now".
Otherwise, the duration is expressed as a combination of
years, days, hours, minutes and seconds.
```
function formatDuration (sec) {
if (!sec) return 'now';
let arr = [], str = '';
const y = Math.floor(sec/365/24/60/60);
if (y) {
str = (y===1) ? y+' year' : y+' years';
arr.push(str);
sec = sec-y*365*24*60*60;
}
const d = Math.floor(sec/24/60/60);
if (d) {
str = (d===1) ? d+' day' : d+' days';
arr.push(str);
sec = sec-d*24*60*60;
}
const h = Math.floor(sec/60/60);
if (h) {
str = (h===1) ? h+' hour' : h+' hours';
arr.push(str);
sec = sec-h*60*60;
}
const m = Math.floor(sec/60);
if (m) {
str = (m===1) ? m+' minute' : m+' minutes';
arr.push(str);
sec = sec-m*60;
}
const s = sec;
if (s) {
str = (s===1) ? s+' second' : s+' seconds';
arr.push(str);
}
return arr.join(', ').replace(/(.*)(,)/g, '\$1\ and');
}
```
***
## Experience
I have no experience in this area.
***
## Education
* **University:** Belarusian National Technical University
* **Speciality:** Economics and company management
***
## English
**A2**