---
title: Live Vehicles
category: Map
order: 3
---

Live Vehicle view provides a real-time view of every vehicle included in your fleet. The Live Vehicle action panel provides several tools to quickly locate an active vehicle within the map. For snow plows and other vehicles with sensors (sweepers, mowers, etc.) the current sensor status is displayed for all live vehicles.

* Selecting a vehicle from the action panel will pan the map and highlight the vehicle.
* The action panel updates in real-time and displays the last message received for the vehicle.
* Vehicles with messages received during the last three (3) hours are highlighted in light blue within the action panel.
* Selecting a vehicle from the map will show a pop-up menu with the last message received for the vehicle.
* Filtering the list of live vehicles by category will filter the map.
    * i.e. Click Plow to only see plows in the map.
    * i.e. Click Sweeper to only see sweepers in the map.

![Live Vehicles](/img/livevehicles.png)

> Note: Some features may not have the expected functionality when a snow event is not in progress.

**Other notes:**

* Vehicle message interval is controlled by the AVL provider configuration. For plows, a 15 second reporting interval is strongly recommended. Please contact the AVL provider support to adjust the reporting interval. Also please note faster reporting intervals will increase data fees with the provider.
* Live vehicle breadcrumbs are styled in the map based on their category and whether they are moving or idle.
* Live vehicles that are treating (i.e. plow down, spreader on, brush on) will be highlighted with a green circle.

![Legend Items](/img/vehicles_legend.png)

* * *
[Next Page](https://primeplow.github.io/Map/historical-vehicles/)