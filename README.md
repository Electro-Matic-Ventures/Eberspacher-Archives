# Eberspacher-Archives
version | to do | next
--------|-------|------
4.00.006 | Station select working with WIP and non-WIP stations. New station button select working. <br/> |
4.00.007 | Array of selectable WIPs returned on selection of one or more WIP stations. <br/> |
4.00.008 | WIP Select fully functional. <br/> |
4.00.009 | Debug selectable WIP list, selected WIP count. Check selected station count for all buttons. <br/> |
4.00.010 | fixed filter on hmi station selection. </br> fixed event for redrawing selectable station when selectable station count is less than viewable station count </br> added state machine to from excel function to manage loading codes on plc power cycle| add selected station data to hmi data structure
4.00.011 | new architecture for settings screen </br> start selected station list hmi driver | Settings Screen: Animations -- moved buffering into child functions </br> updated select wip and select button animations to new format </br> made Part Number: Is Single and Part Number: Is Double functions to increase readability </br> settings screen: line entry driver
4.00.012 | dropzone and line io field drivers working | changed state changes: separated by data type </br> next: total and critical drivers
4.00.013 | select infrastructure in place</br> line and dropzone working on table | updated after a long period
4.00.014 | added wip to settings selected wip table</br> added word wrap | 
4.00.015 | selected wip table animations complete | next up:</br> -  create list for select wip table
4.00.016 | select table array created | next up: </br> selected station table navigation
4.00.017 | select wip table navigation working | next up: </br> select wip table data entry
4.00.018 | identified issue with data entry on wip page | working to correct
4.00.019 | dropzone visibility | invisible when selected stations are 0 or more than 1
4.00.020 | line visibility | invisible when no selected stations or selected stations line names do not match
4.00.021 | wip table navigation visibility | invisible when fewer than 3 wips or stations selected
4.00.022 | single/double part number entry infrastructure | validate part number entry function
4.00.023 | single & double part number entry validated | validate line data entry function
4.00.024 | line data entry function validated | validate dropzone data entry function
4.00.025 | dropzone data entry validated | validate total time data entry function
4.00.026 | total time data entry validated | validate critical time data entry function
4.00.027 | critical time data entry function validated | validate hmi station line data entry function
4.00.028 | hmi station line data entry validated | validate hmi station dropzone data entry functionality
4.00.029 | hmi station dropzone data entry validated | validate hmi station total time data entry functionality
4.00.030 | hmi station total time data entry functionality validated | validate hmi station critical time data entry functionality
4.00.031 | hmi station critical time data entry validated | validate hmi station part number data entry functionality
4.00.032 | address large led display issue | validate wip switchover
4.00.033 | part call row selection performed | load data into barcode udt
4.00.034 | data loaded into barcode udt | add acknowledged button
4.00.035 | acknowledged button added | set ordered state
4.00.036 | ordered state set | set acknowledged state
4.00.037 | acknowledged state set | fix wip switch issue