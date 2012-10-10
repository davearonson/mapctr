Web page to find the center of a bunch of addresses.

This was my first learning experiment with the Google Maps API, but it turned
out to be popular/useful enough to keep around, and do assorted little
improvements on.

It works by first retrieving the latitude and longitude of each address you
enter, and then simply averaging all the latitudes and all the longitudes.
Then it puts a marker at that point, plus all the addresses, and makes sure
it's zoomed out far enough that they're all visible.

There is a live copy at:

https://dl.dropbox.com/u/9324440/mapctr.html .

If you copy this, please use your OWN Google API key, rather than running up my
request count!

Thanks,
Dave
