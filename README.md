# Eberspacher-Archives
version | to do | notes
--------|-------|------
4.00.006 | Station select working with WIP and non-WIP stations. New station button select working. <br/> |
4.00.007 | Array of selectable WIPs returned on selection of one or more WIP stations. <br/> |
4.00.008 | WIP Select fully functional. <br/> |
4.00.009 | Debug selectable WIP list, selected WIP count. Check selected station count for all buttons. <br/> |
4.00.010 | fixed filter on hmi station selection. </br> fixed event for redrawing selectable station when selectable station count is less than viewable station count </br> added state machine to from excel function to manage loading codes on plc power cycle| add selected station data to hmi data structure
4.00.011 | new architecture for settings screen </br> start selected station list hmi driver | Settings Screen: Animations -- moved buffering into child functions </br> updated select wip and select button animations to new format </br> made Part Number: Is Single and Part Number: Is Double functions to increase readability </br> settings screen: line entry driver
4.00.012 | dropzone and line io field drivers working | </br> changed state changes: separated by data type </br> next: total and critical drivers