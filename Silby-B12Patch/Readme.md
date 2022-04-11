Intended to workaround an issue with slot counts as a result of an incompatibility with Silby Overhaul Beta12 and YAML 0.9.1.
<br>Simply replace the existing 'SYO\Resources\Equipment_properties.json' with this one.

It is janky but it instead adjusts the equipment properties using the "SlotFiller" properties to take up the intended slots.
The only gyro not temporarily corrected is the XXL as it is internally trying to take more slots than exist and cannot be adjusted.<br><br>

It is also patched for the cockpits to a very limited extent. I cannot get it to fill both slots for the command console and VDNI as filling 2 slots makes it unable to be used. As a result all cockpits (excluding the small cockpit) will have 1 filler rather than 2 for those that otherwise require it by definition. Had to infer based on existing data what the fields were for the base cockpits such as "COCKPIT_PRIM, COCKPIT_CC, COCKPIT_VDNI".
