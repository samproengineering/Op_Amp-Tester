# Op_Amp-Tester
A low cost and perfboard-friendly board for testing op amp. It's main purpose is to identify counterfeit Op-amps by validating their specifications. Or you can just use to check any op-amp that measures good for your projects. The schematics and layout are provided. <br>
_**Note: that you need to have appropriate measurement equipment such as oscilloscope, multimeter, signal generator and your own power supply to take measurements.**_

## The backstory 
Counterfeit op-amps are very common nowadays especially buying from grey markets such as Aliexpress, Ebay, or other sites. Many people will say "just buy it from reputable electronics distributor", but not everyone can afford an op-amp that potentially cost them a meal each, especially when your projects need multiple of them. This tester is perfect for this purpose as you didn't need to order a custom PCB for the same exact reason, COST SAVING! But a friendly reminder, technically you can only prove that an op-amp is counterfeit because even all the measurements are within specification, it might still be fake. At that point, I will take that as good enough and assume it "real". You could build a test rig using breadboard but it tends to be messy and can be unreliable. 

# Main features 
- Unity gain non-inverting amplifier (for slew rate measurements) 
- Input offset voltage measurement
- Quiescent current (Supply current) measurement
## Bonus features (Configurable from unity gain amplifier) 
- Open loop gain amplifier (non-inverting)
- Configurable gain amplifier (non-inverting) <br>
*Both are less useful than unity gain but you have the options to configure for your needs

# Schematic preview 

# Inputs, Outputs and Configurations 

# How to-

## Measure offset voltage 

## Measure quiescent current

## Measure slew rate 

# BOM (Bill of materials) 
| Item # | Description               | Values | Quantity | Alternative / Notes                                                      | 
|  :---: | :---:                     | :---:  | :---:    | :---:                                                                    |
| 1      | Resistor                  | 10     | 3        |                                                                          |
| 2      | Resistor                  | 10k    | 2        |                                                                          | 
| 3      | Load Resistor             | 1k     | 1        | Other values can be chosen according to your test condition              |      
| 4      | Ceramic Capacitor         | 100n   | 2        |                                                                          |
| 5      | ZIF 16Pin Socket          |        | 1        | 1x 16 pin socket / 2x 8 pin socket / DIY socket from Female machine pin  |
| 6      | Male pin header           |        | 15POS    | Some header can be replaced by breakout wires                            |
| 7      | Female machine pin header |        | 12POS    | Can be omitted according to your needs                                   | 
| 8      | Solid core wire (Jumper)  |        |          |                                                                          | 
| Extra  | Feedback Resistors        |        | 2        | Values according to required gain                                        | 

# How to build 

# Possible improvements / Problems 





