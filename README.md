# mySQM-3D_Anemometer
A 3D printed Anemometer based on the design from mySQM+ DIY SQM Weather Station on Sourceforge.

This is based on the design found here:
https://sourceforge.net/projects/mysqmproesp32/files/Wind%20Speed%20Sensor%20Anemometer/mySQMPROESP-3DPRINTER/

These 3D printed parts are released into the public domain and also follow the copyright indicated in the 
mySQM+ DIY Weather Station found on Sourceforge:
    "COPYRIGHT RESTRICTIONS
    The schematic, firmware and other code and ideas are released into the public domain. Users are free to
    implement these for their personal use, but may NOT sell projects based on (or derived from) this project
    for commercial gain.
    1. You cannot sell kitsets or assembled units to others
    2. You cannot copy the design and code and make your own version to sell to others, even if you make 
       some code changes or change pin designations
    3. You cannot use these designs and code ideas to make your own controller and sell versions of those 
       to others"

Coding for the Anemometer will be based on my code integrated into my existing DIY Weather Station, which will 
be made available on my GitHub in the near future when integration is complete.  Should work fine with the 
mySQM+ DIY SQM Weather Station code too as all critical dimensions remained the same on my re-work.

Main Reasons for Re-Work:
A. Don't like using glue on PETG parts.   Not reliable from my experience.  All parts screw together 
   with internal threads or screws.
B. Wanted to be able to take it apart for repair or updates.   Original relies on press fit for bearing 
   and made assembly/disassembly difficult.
C. Wanted to make the rotating assembly fixed vertically so it could not move up/down.

NOTES:
* Followed original instructions and non-3D parts list as a guide.
* All the original parts should fit and work, minus possibly the Hall Effect Sensor may not mount
  in the slot in my design (taller/wider??). You would have to mount it as done in the original design.
* Purchased all parts in US from Amazon with the following specifications/notes/links:
  - Bearing:  The key specification is this is a 6004 bearing which is a common size.  I purchased 
    a 2RS model (rubber seal on top and bottom) as specified in the orginal guide but did not like
    the friction it created.  While not as good of seal to keep water and dirt out, I ended up
    buying a ZZ model (steel seal on top and bottom).  Much less friction.
    PGN - 6004-ZZ Shielded Ball Bearing - C3-20x42x12 - Lubricated - Chrome Steel
    https://www.amazon.com/gp/product/B07GWZ48SK/
  - Hall Effect Magnetic Sensor: I could not find the "Keyes-024" model on Amazon though there
    are many other brands.  The originally spec'd model offers a digital and analog signal
    output and runs on 3.3V.  The one I purchased only has the required digital output
    and runs on 3.3V or 5.0V. My design has a holder for this sensor.
    There are many other models on Amazon.
    HiLetgo Hall Effect Magnetic Sensor Module 3144E A3144
    https://www.amazon.com/gp/product/B01NBE2XIR/
  - Cable Gland:  I did not use a pre-wired bulkhead connnector.  Instead I used a waterproof
    cable gland size PG7 and some tape. I already have a set of assorted sizes.  Many PG7 
    cable glands are available on Amazon, but here is one example (make sure you get size PG7), 
    looks like the threads are long enough (4 mm needed as I recall, check STL):
    BouPower 20Pcs Nylon Cable Gland Waterproof IP68 Adjustable Cable Connectors Joints with Gaskets
    https://www.amazon.com/BouPower-Waterproof-Adjustable-Connectors-Gaskets/dp/B08QZ97C5B/
  - Magnets:  I already had a supply of magnets but they are readily available on Amazon.
    Personally I like the assortment packs which are more, but I use them for other projects.
    One example of a small pack of 6x3mm magnets on Amazon:
    TRYMAG Refrigerator Magnets 45 Pcs, Small Round Disc Fridge Magnets
    https://www.amazon.com/TRYMAG-Refrigerator-Multi-Use-Cylinder-Whiteboard/dp/B09MRMXMCW
 
 
