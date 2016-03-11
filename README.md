# TimeSpanEmitter
Emit events for a given timespan at a variable playback rate

Initialization example

`TimespanEmitter(start_time, end_time, interval, playback_rate, loop)`

* start_time: Date()
* end_time: Date()
* interval: milliseconds in each step
* playback_rate: rate at whcih to playpack time span eg; 1, 10, 1000
* loop: whether to loop back after end_date and replay
