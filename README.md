# Blazor Animation using tailwind

_based on Chris Sanity github and video_ 

In order to create animation the following steps happen

1. CSS is set on a div or element is set to a start state i.e. opacity 0
2. timer is set to run and fire an event after a period of x miliseconds (say 400)
3. the event sets the CSS on the div or element to a complate state i.e. opacity 100
4. the timer is then disposed


