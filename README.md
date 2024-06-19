# `pmwatch` -- a Pollin' Process Max Memory Watcher

Does what it says on the tin. Written during a meeting I wasn't super involved in.

Licensed under the MIT license.

## Example Usage

Very basic example:
```
[jenluc@enterprise] pmwatch sleep 10
At polling interval of 0.001 seconds, this process took at most 3.25390625 MB of memory
```
(I was surprised sleep took so much memory)

Works with keyboard interrupts, too!
```
pmwatch sleep 100000
(oh shit, i hit too many zeros. Time to do a little Ctl+C)
^CAt polling interval of 0.001 seconds, this process took at most 3.4453125 MB of memory
```
