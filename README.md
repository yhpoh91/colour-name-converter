# Get Colour Name from Hex Value for ExpressJS framework.
-------------------------------------------------------

1. Put file in /utils directory
2. Add the following code:

>var colours = require('../utils/colours');
>colour = colours.getName("30D5D0");

3. Get closest colour in the following format:

>{
>	"hex": String,
>	"name": String
>}

- hex 	:	hex value of the closest colour
- name 	: 	name of the closest colour
