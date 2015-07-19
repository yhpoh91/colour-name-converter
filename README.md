Get Colour Name from Hex Value for ExpressJS framework.
-------------------------------------------------------

\n1) Put file in /utils directory\n2) Add the following code:

-----------------------------------------

\nvar colours = require('../utils/colours');
\ncolour = colours.getName("30D5D0");

-----------------------------------------

\n3) Get closest colour in the following format:

-----------------------------------------
{
	\n"hex": String,
	\n"name": String
\n}
-----------------------------------------

\nhex 	:	hex value of the closest colour
\nname 	: 	name of the closest colour

-----------------------------------------