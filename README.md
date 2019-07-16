# iCalendar
Simple iPhone styled Vanilla JavaScript Calendar Library

```html
<script src="..js/iCalendar.css"></script>
<script src="..js/iCalendar.es5.js"></script>
```
```javascript
var iCal = new iCalendar('calendar');
iCal.render();


var iCal = new iCalendar('calendar');
iCal.render();


//Listen to calendar date selected event
document.addEventListener('iCalendarDateSelected', function(event) {
            console.log(iCal.selectedDate);
});
```
