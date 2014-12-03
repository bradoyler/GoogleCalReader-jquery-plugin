Google Calendar feed reader - plugin to get upcoming events from a *public* google calendar

## Default Options
```js
{
	calendarId:'en.usa#holiday@group.v.calendar.google.com',
	apiKey:'Public_API_Key',
	dateFormat: 'MonthDay',
	errorMsg:'No events in calendar',
	timeZone:'America/New_York',
	futureEvents:false,
	maxEvents: 50
}
```

## Example

```html
<script type="text/javascript" src="http://ajax.googleapis.com/ajax/libs/jquery/1.11.1/jquery.min.js"></script>
<script src="jquery.googlecalreader-1.1.js" type="text/javascript"></script>

<script type="text/javascript">
  $(function() {
    $('#eventlist').gCalReader({ calendarId:'your_calendar@group.v.calendar.google.com', apiKey:'your_public_api_key'});
  });
</script>
<div id="eventlist"></div>
```

