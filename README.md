# Turbo_Expander-in-NGL-fractionation
Energy integration by using Turbo Expander mechanism in process of NGL fractionation.

![image](https://user-images.githubusercontent.com/121662875/230914693-35866208-2730-4e75-8918-6ded640e1758.png)

Schematic diagram of a turboexpander driving a compressor

Softwere use for this simulation :
![Aspen Version](https://img.shields.io/badge/Aspen_Hysys-v12.1-Green)

The Process Flow Diagram from the process

![image](https://user-images.githubusercontent.com/121662875/230912591-333db8fe-2173-4381-89ba-e6fc49226510.png)
The Turbo-Exp provide energy to the Compressor(C-100)

# Summary of view
The feed for this simulation is a Natural gas with carbon dioxide and the carbon chain of the hydrocarbon are set from 1 to 6. The condition at the feed are at high pressure and at standard temperature. The flow continue to a cooler and a separator. The separator is necessary to split the gas and liquid because the expander can only operate with gas. The Turbo-Exp will reduce both pressure and temperature, in this simulation the outpun pressure of the turbo-exp is set so the outlet temperature is calculated by the aspen hysys. The energy from the turbo-exp is transfered to the compressor by mechanical work. The high pressure gas is expanded to produce work that is used to drive the compressor or generator. The PFD will have to place the Turbo-Exp and C-100 as close as possible in the future correction. The high pressure of the gas is favourable condition to make an assumption for the process to be isentropic process.

# The impact and future analysis
The result from the simulation will give the type and size of the compressor that is suitable for the process. The possiblities of multiple Turbo Expander can also be considered if the process will require multiple compressor. The will have to consider split the stream after the separator and then flow to the Turbo-Expander that is connected to the compressors. The decision will have to consider the cost of energy that can be save versus the cost for installing another turbo-exp.

# Made by :
1. Abdul_Hafiz
2. Surayya
