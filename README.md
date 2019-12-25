# OHLightHandle
An openhab Light handle script
Created By Lasse Byrnak

to turn on a light just run the following script:
callscript('bulb1_on')

//What i learned so far is to not have items triggering items triggering items that eventually turn on a bulb. the reaction time will be //devastating going from 2-10 secondes after initial request.
//so keeping the bulb reacting as close to the initial request is a must.

// nice things for the future:
// make the bulb1_on script easy to handle when new bulbs are added / changed / removed
// I would like to have a function based AllLight_on script instead of multiple bulbx_on scripts
