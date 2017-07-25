# Code 301 - Day 11

In lecture for day 11 we recapped the IIFE syntax and usage.  We also spoke a little more about functional programming.  We then switched gears and discussed the Page module.  Page is used for setting up front end navigation routes in a manor analogous to the backend routes set up in a server.js file.  The syntax for route specification is as follows:
  * page(url, callback)

An * can be used as a wildcard for a catch-all route to be used as a 'not found'.  This wildcard route should be specified last in the route specifications or it will override valid routes.
  
