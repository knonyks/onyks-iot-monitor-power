## Things to repair:

#### Testing

- [ ] test measuring voltage with transformer
	- [ ] add 10nF separating cap at ADC inputs
	- [ ] add zener diode for protection at ADC inputs
	- [ ] test with spice (and make note)
	- [ ] check if negative voltage doesn't get clipped
	- [ ] build and test the circuit (and make note)


- [ ] test measuring current with ACS712
	- [ ] add 10nF separating cap at ADC inputs
	- [ ] add zener diode for protection at ADC inputs
	- [ ] test with spice **if model is avalible**(and make note)
	- [ ] check if negative voltage doesn't get clipped
	- [ ] build and test the circuit (and make note)
	

- [ ] preper unused ADC pins for use
	- [ ] add optional voltage divider
	- [ ] add 10nF separating capacitor at ADC inputs
	- [ ] add zener diode for protection at ADC inputs
	- [ ] optional: add some extra connector

#### Schematic

- [ ] change elements size (from 0805 to 0603)
- [ ] calculate max ampreg and power
- [ ] add 4,7k pullup for SPI
- [ ] add smd fuse for 5V
- [ ] add replaceble fuse for 230V relay (high side)

#### PCB

- [ ] add mounting holes
- [ ] import via and track size from JLCPCB
- [ ] make wider gap betwen Low and High side (clerance)(mabe cuts?)
- [ ] add text with voltage and max amperage near power connector
- [ ] add multiple vias to wider tracks
