# TimeSpanEmitter
Emit events for a given timespan at a variable playback rate

Initialization example

`TimespanEmitter(start_time, end_time, interval, playback_rate, loop)`

## Arguments

* start_time: Date()
* end_time: Date()
* interval: milliseconds in each step
* playback_rate: rate at whcih to playpack time span eg; 1, 10, 1000
* loop: whether to loop back after end_date and replay

## Events
* timer: called each step, used to update your visualization
* loop: called at each loop, useful for resetting view after each loop

See [index.html](https://github.com/NationalAssociationOfRealtors/TimespanEmitter/blob/master/index.html) for implementation example
