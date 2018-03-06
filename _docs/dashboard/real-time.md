---
title: Real Time Data
category: Dashboard
order: 1
---

The dashboard provides real-time performance metrics during an active snow event. You can review overall event statistics for previous events, but many of the features are only active during a snow event.

### Event Details
The top portion of the dashboard shows key event information (Event Name, Event Start Date, End Date, Duration, Average Temperature, Precipitation).

![Dashboard](/img/dashboard.png)

### Event Statistics
This table and chart displays percent complete by priority and a break down of treatment (in miles) over several recent time frames (last hour, 3 hours, and since the beginning of the event).

### Event Trends
This chart shows how percent complete has changed over time. This allows you to measure your average cycle time for each priority (i.e. typically three hours of work will result in 50% of priority 1 streets receiving treatment).

![Event Trends](/img/eventtrends.png)
Each line represents a priority, clicking on the line will show the percent complete recorded at that moment in time.

### Current Activity
This table displays many vehicles in your fleet have their ignition on and how many routes have a vehicle deployed on them.

### Vehicles By Priority
This table shows what priority your vehicles are currently deployed on.

![Vehicles By Priority](/img/vehbypriority.png)

### Last Vehicle Message
This is a simple table that updates whenever a new vehicle breadcrumb is received by the system. You can sort the table by each of the columns. The first column (gear) will highlight blue and spin when a recent breadcrumb message is received. Please note this only loads messages received after the dashboard is opened.

![Last Vehicle Message](/img/lastvehiclemessage.png)

### Weather
An hourly and daily weather forecast is provided by Dark Sky. You can click on the Powered by Dark Sky link to visit [darksky.com](http://darksky.com/) for more weather details.

![Weather](/img/weather.png)

### Routes
This table shows the current number of passes, and the total number of passes performed on each route during the selected snow event.

![Routes](/img/routes.png)

* * *

## Events

Event management is a key feature which supports the dashboard metrics. This page is used to start and end snow events and capture snow event updates. Snow events are required to show recent treatment information to the public.

### New Event
Starting an event will impact the internal map, the internal dashboard, and the public application.
* **Internal map:** After an event is started the internal map view will show street segments based on the last time a plow has treated a street segment.
* **Dashboard:** After an event is started the dashboard will start calculating statistics. The statistics shown are specific to the snow event.
* **Public Site:** After an event is started the “treatment” view displayed in the public application will begin showing treatment information.

![Event Start](/img/Event_Start.gif)

### Event Updates
Event updates provide a way to document the snow removal process during an active snow event.
![Event Updates](/img/eventupdates.png)
### End Event
Starting an event will impact the internal map, the internal dashboard, and the public application.

* **Internal map:** Ending an event will clear the map view that shows street segments based on the last time a plow has treated a street segment.
* **Dashboard:** Ending an event will stop the dashboard from calculating statistics.
* **Public Site:** Ending an event will stop the public application from showing the “treatment” view.

* * *

