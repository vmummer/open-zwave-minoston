# open-zwave-minoston
July-07-2022

Added support for Open-Zwave for Minoston MP22ZP zwave Smart Outdoor Plug

1) Add the following to bottom of this file just above '/ManufacturerSpecificData'

~/openwave/open-zwave/config/manufacturer_specific.xml

  <Manufacturer id="0312" name="Minoston">
    <!-- Addded 22-07-20 by Vince Mammoliti vince@afterpoint.ca -->
    <Product config="minoston/mp22zp.xml" id="ff0f" name="MP22ZP Smart Outdoor Plug" type="ff00"/>
  </Manufacturer>



2) Make director minoston and copy mp22zp.xml into it.
