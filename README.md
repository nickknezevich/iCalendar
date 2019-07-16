# iCalendar
Simple iPhone styled Vanilla JavaScript Calendar Library


var iCal = new iCalendar('calendar');
iCal.render();

document.addEventListener('iCalendarDateSelected', function(event) {
            console.log(iCal.selectedDate);
});
