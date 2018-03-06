---
title: real-time
category:
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

## Vehicles

The vehicle management interface provides a list of all vehicles to be displayed within Prime Plow. Filter tools are available to find a specific vehicle in your fleet.

![Vehicles](/img/vehicles.png)

### Add Vehicle
Use this tool to add new vehicles to your fleet. Please note your VIN must match the VIN registered with Networkfleet.

### Change Status
Changing the status will adjust how the vehicle is used within Prime Plow

* **Treating:** Vehicle fully operational and will show treatment and be used for statistics.
* **Not Treating:** Vehicle is operational, but assigned to other work. Any breadcrumbs with the plow down or spreader on will **_NOT _** show treatment or be used for statistics.
* **In Maintenance:** Vehicle has a mechanical issue or is reporting false data. Any breadcrumbs with the plow down or spreader on will **_NOT _**show treatment or be used for statistics.
* **Unassigned:** Vehicle does not have a status set.
* **Retired:** Vehicle is no longer in use. Vehicle will be hidden / removed from live truck views and historic search filters.

### Delete Vehicle
Removes a vehicle from your inventory.

* * *

## Messages

The message management page gives your organization control over the messages displayed in the public application. There are two types of messages to be displayed:
1. **Static Messages:** These messages appear on the right side panel of the public application. These are intended to be used for more permanent messages that provide general information.
2. **Scrolling Messages:** These messages scroll across the public map and are intended to be updated frequently to provide the public with up to date status messages about each snow event.

![Scrolling Messages](/img/scrolling-messages.png)

The following functions are available for both static and scrolling messages:

* **Change Message Order:** Click and drag the messages to re-order the messages.
* **Edit Message:** Click on the message text to edit the message. Click away from the message and your message is automatically saved.
* **Toggle Messages On / Off:** Store common messages and turn them on / off as needed.
* **Delete Messages:** Remove messages you don't need.
* **Add Messages:** Create a new message from scratch.
* **Preview:** Shows a preview of the messages that are turned on.

* * *

## Account

![Account](/img/account.png)

The top right of the menu bar provides an account management tool. The tool allows you to adjust your account settings and logout from the application.

**Account Settings:** The settings page lets you change your name, updated your password, and add / remove user accounts (it  (i.e. name and password. Please note your email address will be your user name when logging into the application. Newly added users will receive an account activation email after being added to the system.

**User Management:** Users can be assigned to several roles. Each role has different functionality within the application.

![User Management](/img/usermanagement.png)

**Events:** This page lets users control the content and configuration of the event updates. The main toolbar includes tools to add new items, preview the update, split the event update into multiple pages, and save the edits made to the page. This tool also includes an optional email distribution list that will send event updates to email addresses you specify.

![Events](/img/eventtoolbar.png)

**Event Items:** You may click on an existing event item or use the + button to add a new event item. Once the event item is activated you may specify the title of the item, the data type,  and the item width. If necessary you can also delete an event update item. After you've edited your event items be sure to save your changes using the main event toolbar.

<img src="/img/itemDetails.png" width="411" height="156" />

**Logout:** Click here to logout of the application.