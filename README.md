# open-zwave-minoston

Added support for Open-Zwave for Minoston MP22ZP zwave Smart Outdoor Plug

add the following to bottom of 

~/openwave/open-zwave/config/manufacturer_specific.xml

  <Manufacturer id="0312" name="Minoston">
    <!-- Addded 22-07-20 by Vince Mammoliti vince@afterpoint.ca -->
    <Product config="minoston/mp22zp.xml" id="ff0f" name="MP22ZP Smart Outdoor Plug" type="ff00"/>
  </Manufacturer>
  
Just above this:
</ManufacturerSpecificData>


make director minoston and copy mp22zp.xml into it.
