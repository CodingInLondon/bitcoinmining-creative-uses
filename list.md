# Creative Uses of Timestamping

This is a collection of concrete examples of usage of Bitcoin mining.

## 1. Become a component of the energy grid

Backgrounders:
- [The Energy Academy](https://platform.modo.energy/phase/channels?wchannelid=wy5tng1x36) maintained by UK company Modo.

### 1. Balance energy grids  

#### Grid balancing in Texas
#### Grid balancing in the UK
#### France
#### Other resources

Live examples of grid balancing:
Grid balancing in Texas 
Power companies need a flexible consumer to absorb excess energy on-demand. Very few industries are able to adapt their energy usage on-demand. Those flexible consumers are rewarded with cheaper electricity or special contracts. 
ERCOT is the grid operator in Texas and proposes demand/response programs to take advantage of curtailment. 
These programs give economic incentives to reduce demand.
For instance electricity customers can sell back to the grid a secured block of power when spot prices are high.
In July 2022 Riot made more revenue by selling power back to the grid than mining bitcoin. This is highly dependent on the type of contract.
electricity prices from wind/solar can sometimes be negative because of limitation of demand and transmission capacity (up to 20% of the time in some areas of central USA). 
Grid balancing in the UK: 
There is a similar program to the US called Demand-Side Response (DSR). DSR assets can include manufacturing plants, refrigeration units, air con, energy storage. They get rewarded for increasing or decreasing their consumption on demand. Bitcoin mining can be just another type of DSR asset.
All this monitoring and on-demand control is software-heavy. Optimize Infrastructure is a UK company that specialises in software optimisers for solar/wind to manage batteries and bitcoin miners. 
There are plenty of short educational videos about the UK energy grid at The Energy Academy.
What about France? France's baseload relies essentially on nuclear energy. You hear about the need for balancing solar and wind, but not so much about nuclear. Yet electricity produced by nuclear power plants at night is mostly wasted. It is not clear what is done with this spare power apart from lighting up motorways. According to Bruno Comby, it would take in theory a handful of power plants around the world to feed the totality of Bitcoin's current energy needs. 

Other resources:
Forbes article on demand/response Why No One Saw The Success of Demand Response Coming.

Note: although not directly related to timestamping, streaming electricity invoice payments over Lightning is a new idea that can help energy companies with their cash flows. Smart meters can send an automated lightning payment every hour, every day or every month. Energy customers see exactly how much they spend in real time and can take advantage of daily fluctuations in energy prices rather than being stuck to a fixed rate. Because payments are continuous and cash final, this gives a financial advantage to energy providers.  
Example: Synota in the US provides such a service, as explained in this video.  

### 2. Finance energy projects

Energy can now be directly monetised. This naturally can help finance construction of new power plant projects. 

Examples: 
- Canada: nuclear Small Modular Reactors (SMRs) could be financed in part with bitcoin mining as explained by Ryan MacLeod here and here. 
- Kenya: Micro hydro-plants
- Congo: 3 hydro plants in the Virunga National Park are used to help finance the park using mining. This is a great story, check out the article from MIT Technology Review.
- Oman: BBGS provides mining containers to the Green Data City project in Oman. The purpose of the project is to bring the carbon share of their electricity from 100% to 50%. Check out Sebastien Gouspillou's announcement at the Africa Bitcoin Conference (in French). 
For more information, check out this report from Arcane Research. 

Other resources:

## 2. Create incentives to collect nasty stuff

Methane gets special attention because its impact on the environment was shown to be 80x worse than CO2. Methane comes from:
holes drilled during oil exploration
rotting rubbish in landfills 
cow poo and other farm waste  
as described by Daniel Batten during Surfin Bitcoin 2022.  

### 1. Pay oil exploration sites to flare gas cleanly

Methane escapes from the ground as a result of oil exploration. Drilling companies are required by regulation to burn it rather than release it. 

Processing methane for bitcoin mining is more cost effective. It is also cleaner than letting a flare burn by itself because of the controlled environment of the turbine. 
According to Jaran Mellerud, gas flaring is 5 times more effective than wind farms in terms of emission avoidance per $1000 investment. 
This video shows how a gas flaring station looks like.
Other example of flaring station in Texas 
Companies active in this field: 
Crusoe Energy
Great American Mining 

### 2. Reward municipalities for capturing methane from landfills

Similarly to gas flaring, there is a regulatory obligation in some countries to collect methane that naturally escapes from landfill. This is how it works.
Municipalities have to build burners to get rid of the methane.
bitcoin miners allow municipalities to:
save on gas burners
generate revenues from the methane
Example: Vespene Energy in the US specialises in landfill methane capture (twitter: https://twitter.com/Vespene_Energy)
Adam Wright from Vespene explains in detail how this works.  

### 3. Reward farms for capturing biogas 

Farm waste also generates gas that can be burnt into Bitcoin using an anaerobic digester. 

Examples:  
farms in Ireland capture biogas with some help from an Irish company called Scilling Digital Mining (twitter https://twitter.com/ScillingMining)
more about anaerobic digesters here. 
Joe Hall from CoinTelegraph made a short documentary interviewing the farmer and detailing the actual set-up
Datafarm Energy in France builds infrastructure to collect gas from biowaste. In order to accelerate the development of their units, they burn the collected gas and mine bitcoin as explained by Stephane Petibon. They also encourage farmers to heat up greenhouses with ASICs instead of buying gas from the grid.

### 4. Reward people for not throwing away used cooking oil

What? Yep, as in the low-grade oil used to fry chips. Here is the background: somewhere in Guatemala, villagers do their cooking with oil then throw it away and it ends up in a nearby lake. LakeBitcoin had the idea of collecting the used cooking oil, burn it and power a home-made bitcoin mining mini-op.
Check out the full story.
watch this video: we are far from the huge clean mining data centres from Texas, which makes it even more cool. 
## 2. Reduce heating bills

ASICs dissipate heat and it’s usually a major problem that miners tackle with noisy fans, immersion cooling or cold climates. But heat can also be a feature.

An ASIC is a specialised hardware designed to spit out SHA256 all day. But from an electrical point of view, it’s just a fancy resistor. We can assume that 1kW sent through an ASIC generates about as much heat as 1kW sent through an electric heater (minus some energy dissipated as electromagnetic radiation). 

In winter, the opportunity is obvious. Even if electricity prices are too high to make mining profitable, the net result is a reduced electricity bill.
Home heating: when everyone in Europe is moaning about winter heating costs, this is the first application that comes to mind. As of December 2022, affordable solutions are starting to appear.
For instance heatbit ships a home heater for a price that is not too shocking ($1199 for a 1400W unit). Their simulator suggests that a unit running 12 hours/day with a bitcoin price of 20K would bring back $15 per month. Of course you wouldn't sell the minted bitcoins in a bear market. Instead you would keep them for your old days or your kids education.
hestiia is a company based in France that makes two products: myEko is a small heating unit for a single room and SATO is a larger water boiler for home central heating.
MinIT water boiler (available in France for €15000)
DCX Bitpod silent mining enclosure for home use
check out this guide from Braiins
Coindesk discussion on home mining
How to build it yourself 
Industrial heating: because Bitcoin mining scales so well, the case for industrial heating makes even more sense. Greenhouses need heat. Buildings need heat. Entire districts need heat. Why use expensive fuel when you can use electricity with a Bitcoin discount? Check-out Jaran Mellerud's comments on heat re-use  
Whisky distillery in Canada with a custom-made whisky tumbler made by Mintgreen. Check out a video of this special boiler here.
District heating in North Vancouver, Canada with digital boilers from Mintgreen discretely stored in a mechanical room. (twitter https://twitter.com/MintGreenHQ).
Agriculture heating + district heating in the US with liquid cooling boilers built by Sai Tech. 
Greenhouse heating: example of flowers in the Netherlands 
Warehouse heated by Bitcoin Brabant in the Netherlands
Hotel rooms heated by DCX Immersion Mining 
Dried fruits: in Africa there is an industry around the preparation of dried fruits which requires the production of hot air. Sebastien Gouspillou explains how BBGS works on a project in Congo looking at using the heat produced by ASICs to dry up fruits. This is cheaper than using diesel generators.
More on heat re-use in this post from Nico Smid. 

It used to be a niche DIY thing but now you can find a variety of solutions that are easy to install with a reasonable upfront cost. We have reached a point where if you are still using electricity for heat without mining, you are losing out.

## 3. Non Sustainable Uses of Timestamping

Some situations are not so Disneyland. But with time they should eliminate themselves because they're not viable economically. 
 
### 1. Compete with residential users for the same electricity source. 
Example: State of New York: metered electricity was very cheap because of the presence of hydro power in the region. A few years ago, miners took advantage of those low prices, which resulted in higher prices in some situations. Local citizens complained. In some cities, authorities declared a moratorium on bitcoin mining until new special tariffs are worked out. This year in 2022 a new moratorium was proposed to suspend mining that is not based on 100% renewable.
Counter-example: Europe. If you live in Europe in 2022 and you are suffering because electricity prices are too high and you don’t know whether you can afford heating your home this winter, no need to get angry at the timestamping industry: you are not competing for electricity with them. They don't want your electricity. Unlike residential consumers, bitcoin miners are not a captive audience and can move their rigs wherever power is cheap. There is very little bitcoin mining in Europe precisely because electricity is too expensive. According to Jaran from Arcane, mining in Europe happens only in  
Northern Sweden (hydro and wind), presence of a demand/response program
Northern Norway (100% hydro)
Iceland (geothermal and hydro)

### 2. Use fossil fuels

Now fossil fuels represent a minority of the energy sources used to produce the electricity used by Bitcoin mining globally. 
Energy mix is 59.4% sustainable according to the latest BMC report. See also the breakdown calculated by Daniel Batten.
However coal is still the number two energy source at 22.92% according to Daniel Batten (it used to be number one at the time when mining was happening in China).
Logically fossil miners will be the first to turn off their ASICs when the bitcoin price is too low or the network difficulty is too high and therefore will disappear over time as explained by Sebastien Gouspillou here and here (Théorie du dernier survivant). 
Mining with fossil can’t be profitable in the long term because of rising oil and gas prices.
Fossil fuels are normally the most expensive part of an energy distribution stack and are typically used in peaker plants (power plants that activate only at peak times, when demand is too high and cannot be met by the other cheaper sources).
Coal/fuel/gas are controllable sources therefore do not offer the same opportunities as intermittent sources:
no excess energy to negotiate down the price 
no demand/response programs
depending on the jurisdiction, there is political pressure to get away from non renewables (regulation, fines, extra taxes, moratoriums, bans). 
Clearly using fossil is not a great strategy for Bitcoin mining, unless we're talking about:
methane burnt from flaring
burning natural gas that escapes naturally
methane captured from landfill 
gas captured from farm waste.
