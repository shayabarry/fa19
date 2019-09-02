---
layout: page
title: Calendar
nav_order: 2
description: An embedded Google Calendar displaying the weekly event schedule.
---

# Calendar

<!-- <div id="fullcalendar"></div>

<!-- <link rel="stylesheet" property="stylesheet" href="https://unpkg.com/@fullcalendar/core/main.css">
<link rel="stylesheet" property="stylesheet" href="https://unpkg.com/@fullcalendar/timegrid/main.css"> -->
<!-- <script src="https://unpkg.com/@fullcalendar/core/main.min.js"></script>
<script src="https://unpkg.com/@fullcalendar/daygrid/main.min.js"></script>
<script src="https://unpkg.com/@fullcalendar/timegrid/main.min.js"></script>
<script src="https://unpkg.com/@fullcalendar/google-calendar/main.min.js"></script> -->

<style>
.fc table {
  margin-bottom: 0;
}
</style>
<!-- <script>
document.addEventListener('DOMContentLoaded', function() {
  new FullCalendar.Calendar(document.getElementById('fullcalendar'), {
    plugins: ['dayGrid', 'timeGrid', 'googleCalendar'],
    header: {
      left: 'title',
      right: 'today prev,next',
    },
    nowIndicator: true,
    height: 'auto',
    minTime: '09:00:00',
    maxTime: '21:00:00',
    allDaySlot: false,
    slotEventOverlap: false,
    defaultView: 'timeGridWeek',
    // THIS KEY WON'T WORK IN PRODUCTION!!!
    // To make your own Google API key, follow the directions here:
    // http://fullcalendar.io/docs/google_calendar/
    googleCalendarApiKey: 'AIzaSyDRIz3tmchcYjyh1o4VTLj1Y4ciIJDEyjg',
    // US Holidays
    eventSources: [
      {
        googleCalendarId: 'berkeley.edu_in9qvsg9rsv5r35la4oufrq2tk@group.calendar.google.com',
        className: 'data 100',
      },
    ],
  }).render();
});
</script>

 
<script src="../assets/js/calendar.js"></script>
<script src="../assets/js/gcal.js"></script> -->

<iframe src="https://calendar.google.com/calendar/embed?height=600&amp;wkst=1&amp;bgcolor=%23ffffff&amp;ctz=America%2FLos_Angeles&amp;src=YmVya2VsZXkuZWR1X2luOXF2c2c5cnN2NXIzNWxhNG91ZnJxMnRrQGdyb3VwLmNhbGVuZGFyLmdvb2dsZS5jb20&amp;color=%233F51B5&amp;mode=WEEK" style="border-width:0" width="800" height="600" frameborder="0" scrolling="no"></iframe>

<br>

<iframe src="https://calendar.google.com/calendar/embed?src=berkeley.edu_1lstt6addsnlemmfisn40pbulg%40group.calendar.google.com&ctz=America%2FLos_Angeles&amp;mode=WEEK&amp;color=%233F51B5" style="border: 0" width="800" height="600" frameborder="0" scrolling="no"></iframe>