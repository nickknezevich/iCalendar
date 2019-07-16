# iCalendar
Simple iPhone styled Vanilla JavaScript Calendar Library


var iCal = new iCalendar('calendar');
iCal.render();


//Listen to calendar date selected event
document.addEventListener('iCalendarDateSelected', function(event) {
            console.log(iCal.selectedDate);
});
