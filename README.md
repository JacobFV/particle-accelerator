# particle-accelerator

## Background and Theory

A quick Google query of "fusor" yields dozens of do-it-yourself articles on how to construct an endothermic dueterium fusion reactor. The website https://fusor.net/ provided much essential information. I extracted the following information from the articles listed below:  

- https://www.instructables.com/id/How-to-Build-a-Fusion-Reactor-and-Become-Part-of-t/
  - 120V-2kV microwave transformer + high voltage rectifier
- https://www.instructables.com/id/Build-A-Fusion-Reactor/
  - 40 kV 10mA supply (negative polarity) from 
  - 75 millitorr primary vacuam pump in addition to a secondary oil diffusion or turbopump
  - lead shielded camera viewport
  - 50-100k leakage ballast resistor
- https://www.instructables.com/id/Real-Life-Arc-Reactor-a-Working-Fusion-Reactor-Mod/
  - used a ZVS driver with flyback transformer
  - single vacuam pump
- https://www.discovermagazine.com/the-sciences/how-to-build-a-usd1000-fusion-reactor-in-your-basement
  - 20kV 10mA
  - "A two-stage roughing pump \[...\] Then use a turbo or oil diffusion pump to reach a high vacuum"
- https://makezine.com/projects/make-36-boards/nuclear-fusor/
  - Neon sign transformer (120V-12kV) + half bridge reactifier (output 0-6kV 3mA)
  - 0.025 mmHg (~3 Pa)
  
  
All the tutorials stressed the importance of maintaining high chamber vacuam by avoiding fingerprints or other contaminants. For this reason, vacuam pumps do not appear a best choice for second stage chamber evacuation.

Most projects employed ordinary glass jars to construct the chamber walls

### Theory

## Methods

## Design

I will distill dueterium from water by staged electrolysis

In addition to energy imparted from electrostatic acceleration, I will eploy a magnetic pinch towards the center of the accelerator to both increase particulate density and radially confine the collided particles logner. I hope this magnetic field will maintain a higher reaction reaction profile for longer time which may increase internal energy gain.

### Sourcing

| Component | Notes | Price | Delivery |
| ---- | ---- | ---- | ---- |
| [3.5CFM Rotary Vane Vacuum Pump](https://www.ebay.com/itm/142345178028) | Single stage. 5 Pa ultimate vacuam | 54.65 USD | 7/24-7/28 |
| [1000kV Generator](https://www.ebay.com/itm/DC-3-6V-6V-Boost-Set-up-to-DC-400kV-High-Voltage-Generator-Power-Module-Tool/133470018966?epid=1862012138&hash=item1f136edd96:g:~AoAAOSwQiJfDXFp) | 3.7-6V 2-5A input | 9.52 USD | 8/4-8/5 |


## Conclusions and Future Work

To do:

Level I:
- [ ] radiation (neutron, detection
- [ ] deuterium centrifuge distillation
- [ ] tighter and pulsed magnetic confinment

Level II:
- [ ] continuous neutron emmission for
  - dueterium/tritium production
  - magnetically confined neutron beam collisions
- [ ] antiproton pair production, isolation, cooling with electrons, and antihydrogen

for these future ambitions, I will need to read:
- https://arxiv.org/pdf/2004.13103.pdf
- https://en.wikipedia.org/wiki/Fusor
