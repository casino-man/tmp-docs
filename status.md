## In short

### Casino Dog Plugins
Casino Dogs is simple PHP package that works with Laravel 9.* and PHP 8.1+. It's goal is to parse demo/fun mode casin slots and turn them in full fletched real-money slotmachines and gaining full control on outcome of it's game result.

### Regular Slotmachine Event
If you are newer, it is first important that you understand how slotmachines are being delivered to casino's for use.

Below a schematic of how a _unmodified_ slotmachine spin is handled. This is a pretty standard game-flow (chart is an actual production one of [Mascot Games](http://ns327423.ip-37-187-110.eu/static/api/customer/)) within casino industry:







The following functions can be considered main functions and are essential:

Parse demo-mode games, turn these in-to real-money currency games, fetching the player balance, fetching game events to send results to fetch 
