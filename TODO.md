#### List of tasks that need to be completed before the EFIS is flight-worthy

- [ ] Add debouncing circuit to button board
- [ ] Add pullup resistor to ADS1118 CS line
- [ ] Add pullup resistor to thermocouple inputs to prevent floating while unconnected
- [ ] Remove R3 and R4
- [ ] Remove tach input voltage divider and replace with series 1k
- [ ] Change Vref on EGT sensor


#### List of tasks that would be nice but not necessary

- [ ] Flip LCD connector to align with LCD board.
- [ ] Move serial to port 1 for better arduino compatability
- [ ] Add FPC screen interconnect
- [ ] Replace crystal with larger form factor for ease of assembly
- [ ] Remove extra pad on reset button
- [ ] Make tach circuit compatible with open-collector sensors (Lycoming)
- [ ] Move transistor from underneath DSUB
