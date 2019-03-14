---
title: Event Management
category: Management
order: 1
---


Event management is a key feature which supports the dashboard metrics. This page is used to start and end snow events and capture snow event updates. Snow events are required to show recent treatment information to the public.

### New Event

Starting an event will impact the internal map, the internal dashboard, and the public application.

* **Internal map:** After an event is started the internal map view will show street segments based on the last time a plow has treated a street segment.
* **Dashboard:** After an event is started the dashboard will start calculating statistics. The statistics shown are specific to the snow event.
* **Public Site:** After an event is started the “treatment” view displayed in the public application will begin showing treatment information.

![Event Start](/img/NewEvent.gif)

**Event type:** An event type can be added to denote the different treatment activity taking place (i.e. mowing, snow, leaf).
**Event type filter:** An event type filter will be established by developers upon onboarding and when new event types are created. For each event type, filters can be set to control how vehicles mark road treatment. The following treatment scenarios are possible:
* Vehicle status set to treating and no event type filter set - Vehicle marks roads as treated
* Vehicle status set to treating, event type filter set, and no criteria match - Vehicle does NOT mark roads as treated
* Vehicle status set to treating, event type filter set, and all criteria match - Vehicle marks roads as treated

### Event Updates

Event updates provide a way to document the snow removal process during an active snow event.![Event Updates](/img/eventupdates.png)

### End Event

Starting an event will impact the internal map, the internal dashboard, and the public application.

* **Internal map:** Ending an event will clear the map view that shows street segments based on the last time a plow has treated a street segment.
* **Dashboard:** Ending an event will stop the dashboard from calculating statistics.
* **Public Site:** Ending an event will stop the public application from showing the “treatment” view.

---
[Next Page](https://primeplow.github.io/management/vehicles/)