# open-zwave-minoston
<meta name="google-site-verification" content="VME-I6Lwa4Oeg5xOyA4gV2E3AYci2dhEpQb_Y-oNoiY" />
July-07-2022

Added support for Open-Zwave for Minoston MP22ZP zwave Smart Outdoor Plug

Currently using this in my Domoticz deployment. (/home/domoticz/Config)

1) Add the following to bottom of this file just above '/ManufacturerSpecificData'

~/openwave/open-zwave/config/manufacturer_specific.xml
- This could be in the directory called Config 

\<Manufacturer id="0312" name="Minoston"\> <br>
 &nbsp;&nbsp; \<!-- Addded 22-07-20 by Vince Mammoliti vince@afterpoint.ca --\> <br>
 &nbsp;&nbsp; \<Product config="minoston/mp22zp.xml" id="ff0f" name="MP22ZP Smart Outdoor Plug" type="ff00"/\> <br>
\</Manufacturer\> <br>


2) Make a directory called minoston and copy mp22zp.xml into it.

Drop me an email if you found this use full.
