node-red-node-random
====================

A <a href="http://nodered.org" target="_new">Node-RED</a> node that when triggered generates a random number between two values.

Install
-------

Run the following command in your Node-RED user directory - typically `~/.node-red`

    npm install node-red-node-random
    

Usage
-----

A simple node to generate a random number when triggered.

If you return an integer it can include both the low and high values.
`min <= n <= max` - so selecting 1 to 6 will return values 1,2,3,4,5 or 6.

If you return a floating point value it will be from the low value, up to, but
not including the high value. `min <= n < max` - so selecting 1 to 6 will return values 1 <= n < 6 .

**Note:** This generates **numbers**.
