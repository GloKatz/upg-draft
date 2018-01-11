<h2>V.12 Fuzzy Search for Address Functions 1, 1A, 1B, and 1E</h2>  

Geosupport processes situations where there is only one possible valid similar name and that valid similar name is created by adding the word EAST or WEST to the front of the input street name (in other words, the input street name is a front-truncated street name).  For example, if a user supplies 212 146 STREET in Manhattan as the input to a Function 1, 1A, 1B or 1E call, Geosupport recognizes that 146 Street does not exist in Manhattan.  Since only WEST 146 STREET exists (there is no East 146 Street), Geosupport will accept the call with a warning message indicating that West 146 Street is assumed.