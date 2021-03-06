## welcome to the green-EE page!

A directory of resources for building helpful electronics in a sustainable, ethical, and thoughtful way.  
A starting point – not exhaustive.  
[Submit links here!](https://bit.ly/glinked)

#### Questions to address:
* [What impact can we individuals actually have?](https://github.com/alexglow/green-ee/wiki/Responsibility)  
* [Why am I building a new thing?](https://github.com/alexglow/green-ee/wiki/Why-build%3F)  
* What sustainable materials, processes, power sources, and so forth can I use in my project?  
* If I have a hardware business, how can I run that sustainably – from the website to the packaging and shipping?  
* How can we employ Reduce, Reuse, **Repair**, Recycle ([and even Rot!](http://www.tri-citiesdisposal.com/the-five-rs)) to reduce waste and environmental damage?  
* How can I use my skills and passion to help solve big problems (even in little chunks)?

## Building and shipping hardware

### Design

#### Materials
* Tips on [lead-free solder](https://hackaday.com/2020/01/28/lead-free-solder-alloys-their-properties-and-best-types-for-daily-use)
* [Can a smartphone be sustainably manufactured?](https://www.cyrclephone.com/blog/can-a-smartphone-be-sustainably-manufactured) – In-depth research by Christina Cyr while building the Cyrcle Phone
* [Jiva Materials](https://www.jivamaterials.com/): Fully recyclable and biodegradable PCB substrate!
* [Sustainable materials for design](https://www.loomia.com/blog/sustainable-materials-for-design) – from [LOOMIA](https://www.loomia.com/) Soft Circuit Systems
* [Fabrication with recycled plastic, cardboard, and more](https://www.youtube.com/watch?v=SKfhnDZ3iBE&list=PLsRBa4uXjihZwcYrwwuPhsYxWtFwMBqDF&index=15): Agustín Arroyo talks about 3D-printing molds to recycle cardboard into desk objects, packaging, etc. – and using DIY recycled plastics for 3D printing / vacuum forming!
* [Precious Plastic](https://preciousplastic.com/): Highly developed guides, machines, and bazaar for recycled plastic
* 3D printing filament:
    * [Article from All3DP comparing various recycled filaments](https://all3dp.com/2/recycled-3d-printer-filament-brands-compared/)
    * [U-HIPS filament from Closed Loop Plastics on MatterHackers](https://www.matterhackers.com/store/c/closed-loop-plastics) – 100% recycled from post-consumer plastic cups and lids
    * [taulman3D Enviro 100% Recycled PETG Filament](https://taulman3d.com/enviropetg.html) – on recycled cardboard spools!
    * [Re:3D's GIGABOT X](https://re3d.org/gigabot) can print with flakes or pellets of shredded plastic waste! No need to even process it into filament, store it on spools, etc.
        * Also: [knowledge base](https://re3d.zendesk.com/hc/en-us/categories/360001620911-MATERIALS) with lots of info about 3D printing with reclaimed plastics, materials testing procedures, etc.
* [Use cardboard to prototype](https://www.hackster.io/glowascii/f3nr1r-fennec-companion-ai-robot-prototype-d71dca) (a little obvious, but hey!)
* [Inventory of Carbon & Energy Database](https://circularecology.com/embodied-carbon-footprint-database.html): a free online resource with information about the embodied carbon of more than 200 materials.

#### Physical design
###### What can you change about your device to make it integrate better with the environment?
* BoM: lower the parts count?
* Enclosure:
    * Fewer, more versatile, more efficient enclosure parts = less wasted material and less energy to print
    * Can you design it to print without support?
* Simple tweaks: [black paint on 1 blade of a wind turbine helps protect birds!](https://arstechnica.com/science/2020/08/black-paint-on-wind-turbines-helps-prevent-bird-massacres)

#### Power
* Sources
    * Solar power?
        * [PiJuice](https://www.pishop.us/search.php?search_query=pijuice&section=product)
        * [Becky Stern's free solar class](https://www.instructables.com/Solar-Class)
    * Wind power?
        * [Texenergy "Infinite Air" portable wind turbine](https://www.ostsome.com/products/texenergy-inifnite-air-portable-wind-turbine) with USB output
    * Drive low-drain projects from a single "dead" AA/AAA battery, using the Joule Thief circuit
        * [Joule Thief PCB](https://www.hackster.io/glowascii/joule-thief-pcb-651d67)
    * Crank power??
* Better batteries
    * [LiFePO4](https://en.wikipedia.org/wiki/Lithium_iron_phosphate_battery#Advantages_and_disadvantages): Less-harmful batteries, with fewer conflict minerals (as seen in the MNT Reform)
    * [Replaceable batteries](https://www.ifixit.com/Right-to-Repair/Repairable-Products) extend the life of each product
    * Lithium battery recycling is becoming an option – good to look into if you plan on using this type of batteries
* Time on grid
    * [Energy Upgrade California](https://energyupgradeca.org/time-of-use): "From 4 to 9PM, energy demand is high, and less wind and solar power is available. By using less electricity during these hours, you can ensure that your energy is coming from cleaner sources."
        * Can you design or program your product to optimize energy usage around specific times of day, or availability of sustainable energy sources?
        * Charge during off-hours, then run off the battery during peak usage hours?

#### Repairability / Extending your product's lifespan
###### Everything designed for repair is also designed for learning!
* Design for repair:
    * Modularity
    * Fasteners instead of glue
    * Commonly available parts
    * Clear cases?
    * Manuals / public schematics
        * [MNT Reform](https://mntre.com/reform2/handbook/schematics.html)
        * [3DR tutorials](https://www.hackster.io/3dr)
* iFixit:
    * [How to design electronics for repair](https://www.ifixit.com/News/3950/what-tech-manufacturers-have-wrong-how-to-design-electronics-for-repair)
    * [Product design blog posts](https://www.ifixit.com/News/category/product-design)
* Open source!
* Even large tech corporations ([Apple](https://www.apple.com/newsroom/2021/11/apple-announces-self-service-repair), [Samsung](https://news.samsung.com/us/samsung-self-repair-program-ifixit-customer-first-care-experience) with iFixit) are now providing repair parts & know-how to consumers!

#### Afterparty
###### Revive existing tech, rather than throwing it out – or adapt it, instead of building a Whole New Thing
* With hardware, like...
    * Joey Castillo's [Sensor Watch](https://www.crowdsupply.com/oddly-specific-objects/sensor-watch) – new life for the Casio F-91W!
    * Zach's [Virtual Boy ribbon cable replacement](https://segasonicfan.wixsite.com/retro/virtual-ribbon)
    * MNT Research: [New brains for classic Amigas](https://shop.mntmn.com/products/zz9000-for-amiga-preorder)
    * [LSDj](https://www.littlesounddj.com/lsd/index.php) is a system designed to be loaded onto a custom cartridge and run on a GameBoy – using that whole platform by adding only a little piece. (And it's RAD!)
* With software, like...
    * [Rebble](https://rebble.io) – indie replacement for the retired Pebble Watch infrastructure
* By repurposing, like...
    * [Wearable PCBs](https://www.hackster.io/glowascii/ouija-esp8266-programmer-planchette-d2c033) – circuit boards that also work as attractive earrings / key fobs / art objects, if they become obsolete/nonfunctional (or if prototypes don't work)
    * XY plotters from old disk drives
* Reclamation
    * Provide e-waste/recycling services when customers ship their items back ([required in some places](https://www.umweltbundesamt.de/en/topics/waste-resources/product-stewardship-waste-management/electrical-electronic-waste))

#### Bonus: Open design & manufacturing options
###### Better access, more repairability! ✨
* PCB design
    * [KiCad](https://www.kicad.org)
* 3D modeling
    * [OpenSCAD](https://openscad.org)
* 3D printers
    * [Lulzbot](https://ohai.lulzbot.com) – repair service, lots of tutorials, 3D-printable replacement parts!
    * [Prusa](https://github.com/prusa3d)
* Pick'n'place assembly
    * [OpenPNP](https://openpnp.org)
    * [LumenPNP](https://opulo.io)
    * [Pixel Pump](https://www.crowdsupply.com/robins-tools/pixel-pump): "An open source manual pick and place machine for PCB artisans" (cool vacuum pen with foot pedal)
* To be added: Leon Anavi's talk on this subject from Open Hardware Summit '22

### Business

#### Selling
* [Made-to-order as a sustainable model for fashion tech](https://www.youtube.com/watch?v=JzP0p8SdPTQ&list=PLsRBa4uXjihZwcYrwwuPhsYxWtFwMBqDF&index=4) – Kitty Yeung
* Seconds (see [Oskitone](https://www.instagram.com/p/CXegwO6v6Qh)): Selling less-than-perfect items at a discount
* [Stripe Climate](https://stripe.com/climate): Direct a fraction of your revenue toward carbon removal

#### Packaging + shipping
* Matt Johnson ([Bare Conductive](https://www.bareconductive.com/)) on packaging postponement / "just in time" product bundle assembly
    * [Part 1](https://www.youtube.com/watch?v=yjLgxadVfFk&list=PLsRBa4uXjihZwcYrwwuPhsYxWtFwMBqDF&index=100): efficiency, usefulness, fewer SKUs
    * [Part 2](https://www.youtube.com/watch?v=p9l4Hz8798s&list=PLsRBa4uXjihZwcYrwwuPhsYxWtFwMBqDF&index=99): labor, materials use, waste stream
* [Re-used and compostable packaging](https://www.instagram.com/reel/Caprx5VMMg9/?igshid=NDA1YzNhOGU=) – Becky Stern
* [Buy stickers for re-used packaging](https://www.etsy.com/market/reused_box_sticker) – Etsy
    * [Or a stamp](https://www.etsy.com/listing/1021964236/packed-with-reused-materials-stamp-for) (even better!)
* Recycle/biodegradable packing material
    * Paper: [HexcelPack](https://www.hexcelpack.com), [Geami](https://www.ranpak.com/solutions/wrapping), etc.
    * Biodegradable packing peanuts: [U-Haul](https://www.uhaul.com/MovingSupplies/Packing-Supplies/Biodegradable-Packing-Peanuts/?id=730), [Uline](https://www.uline.com/BL_2001/Biodegradable-Peanuts), etc.
    * [Compostable small plastic bags](https://www.clearbags.com/4-1-2-x-5-9-16-flap-premium-eco-clear-bags-100-pieces-gc54s.html) of various sizes!
    * Kraft paper packing tape or tape-less packaging
* Comprehensive system: [LimeLoop](https://thelimeloop.com) – "combines reusable packaging and smart technology... using fewer resources and keeping packaging out of the landfill." Women-owned.

#### Logistics
* Travel
    * Expense carbon offsets for your work travel! (Look into local options first)
    * Choose the most carbon-efficient options for your route ([carbon calculator](https://calculator.carbonfootprint.com/calculator.aspx?tab=3), [BetterWay visualization](http://better-way.herokuapp.com)). Sometimes there's a train! Sometimes flying is actually better than driving alone.
    * Virtual events, telepresence, and remote work where possible
* [Solar-powered office?](https://www.youtube.com/watch?v=uobUwjCLfok) – Highly-rated solar power tutorial
* More sustainable website options
    * [Low Tech Magazine](https://solar.lowtechmagazine.com) – This site runs on a solar-powered server in Barcelona! It gives info on sustainable power systems (including solar and bike power, traditional heating, sustainable waste systems, etc.)
        * [Solar Web Design](https://github.com/lowtechmag/solar/wiki/Solar-Web-Design)
        * [How sustainable is a solar powered website?](https://solar.lowtechmagazine.com/2020/01/how-sustainable-is-a-solar-powered-website.html)
    * [Branch Magazine](https://branch.climateaction.tech): "This site [changes its design](https://branch.climateaction.tech/issues/issue-1/designing-branch-sustainable-interaction-design-principles) based on the quantity of fossil fuels on the grid to stay inside a carbon budget at all times."
* Sustainable snacks! Try fueling your work with cricket protein bars, like [EXO](https://exoprotein.com/collections/all-products) or [BugOut](https://bugout.bar/products/cricket-protein-bar-box-of-12-chocolate-brownie)
* Team building? Look up local Fixit Clinics / Repair Cafés: meetups where people are invited to bring broken appliances, and volunteers will help fix them

## Project inspiration
######  Hack the future! How can you apply your passions to real-world issues? What problems _do_ have technological solutions? Some ideas to get the creativity flowing...
* Agriculture:
    * vertical farming and other structural/technical innovations
    * sustainable options for materials and food: seaweed, hemp, [edible insects](https://www.hackster.io/sustainable-living-lab/environmental-sensing-for-black-soldier-fly-larvae-cb54e9) for humans/livestock...
    * Composting: [Compost Professor](https://www.hackster.io/darian-johnson) and other projects by Darian Johnson
* Drones for good:
    * Humanitarian: Disaster relief, search and rescue, [medical/PPE delivery](https://flyzipline.com), communication
    * Renewable energy inspection, cleaning, and maintenance
    * Infrastructure inspection
    * Air duct inspection
    * [Aerial methane leak detection](https://kairosaerospace.com/methane-detection)
    * [Seed dispersal for wildfire recovery](https://droneseed.com)
    * UAV swarm displays instead of fireworks: better for wildfires, better for veterans and pets/wildlife
    * Waste management, flood risk mitigation, biodiversity conservation, open UAV data for climate resilience urban planning – UNDP, ["The Sky's Not the Limit: How Lower-Income Cities Can Leverage Drones"](https://www.undp.org/sites/g/files/zskgke326/files/2022-05/UNDP-The-Skys-Not-The-Limit.pdf), page 106+
    * Jinger Zeng on [positive applications for UAV technology](https://www.youtube.com/watch?v=_UqYqh233cw&list=PLsRBa4uXjihZwcYrwwuPhsYxWtFwMBqDF&index=3&t=818s)
* Projectors / non-destructive "light graffiti": spread information/awareness and apply political pressure
    * [Handheld Light Graffiti Projector](https://github.com/DisruptivelyUseful/handheld-light-graffiti): tutorial by Claire Cassidy
    * [Projection Rebellion](https://www.instagram.com/projectionrebellion)
* Political action:
    * Helping people vote (voter education, organizing rides, streamlining the ID application process, ...)
    * Raising awareness and pressuring lawmakers on important legislation
    * Improving access to the political system
* Machine learning / AI:
    * Predictive maintenance – use sensors to detect potential machine/infrastructure failures before they happen
    * [Climate Change AI](https://www.climatechange.ai)
    * [Predictive Analytics World Climate](https://predictiveanalyticsworldclimate.com): Conference on industry applications of machine learning in climate tech
    * ["Computer vision in the climate space"](https://www.youtube.com/watch?v=SKPoEfvA2cc), ft. Kaushal Bhavsar – how CV tech "helps find viable roof tops for installing solar panels in Singapore"
* Protection of wildlife and natural resources against poaching, logging, etc.
    * [Smart Parks](https://www.smartparks.org) / [ElephantEdge](https://www.hackster.io/contests/ElephantEdge)
    * [OpenCollar](https://www.smartparks.org/opencollar-io) (Smart Parks): "a conservation collaboration to design, support, and deploy open-source tracking collar hardware and software for environmental and wildlife monitoring projects"
* Environment monitoring and recording over time
    * [Crowdsourced air quality](https://www2.purpleair.com/collections/air-quality-sensors)
    * [Greenhouse gas emissions](https://www.ribbitnetwork.org)
    * [Seismic activity](https://shop.raspberryshake.org)
    * [Water quality](https://cleanwaterai.com)
    * [AudioMoth](https://www.openacousticdevices.info) for wildlife monitoring
    * [SlothBot](https://www.futurity.org/slothbot-conservation-robot-2388952)! Environmental sensing, at a slow pace, within a specified area
* Low-impact, low-cost scientific devices (e.g., [Spectra / OpenEIT](https://openeit.github.io/docs/html/index.html) for imaging)
* Waste reduction or reclamation
    * One of many technologies where microbes are being used!
    * [Horge.eu](https://www.horge.eu/en): Converting diverse types of waste to syngas
* Telepresence
* More recyclable and biodegradable – even [edible?](https://www.hackster.io/glowascii/synthenada-empanada-synthesizer-3b1335) – technologies ;)
* Bio-collaboration, microbial technology, and mycelia (fungi): Collaboration with other species is an incredible way to produce some magical results!
    * Bioremediation with microbes, [breaking down plastics in the environment](https://journals.asm.org/doi/10.1128/mBio.02155-21) – "potential to degrade 10 different plastic types"
    * Bioreactors for power: [algae panels on the façade of BIQ apartment building in Hamburg](https://www.internationale-bauausstellung-hamburg.de/en/themes-projects/the-building-exhibition-within-the-building-exhibition/smart-material-houses/biq/projekt/biq.html)
    * [Pleurotus fungus](https://www.youtube.com/watch?v=JJfDaIVl-tE) can digest crude oil, cigarette butts, glyphosate herbicide, and more!
    * [Microbial nitrogen](https://www.pivotbio.com) for agriculture
    * [Microbes producing fuel](https://www.nsf.gov/discoveries/disc_summ.jsp?cntn_id=115514&org=NSF)!
    * [Clams as water quality sensors in Poland](https://www.thefirstnews.com/article/documentary-turns-life-saving-clams-used-to-detect-water-pollution-at-warsaw-pumping-station-into-internet-stars-13119)
* [Hackaday Prize 2022](https://hackaday.io/contest/184555-supplyframe-designlab-2022-hackaday-prize) – inspiring projects for...
    * [Planet-Friendly Power](https://hackaday.io/contest/184555-supplyframe-designlab-2022-hackaday-prize/log/204304-challenge-1-planet-friendly-power)
    * [Reuse, Recycle, Revamp](https://hackaday.io/contest/184555-supplyframe-designlab-2022-hackaday-prize/log/204305-challenge-2-reuse-recycle-revamp)
    * [Hack it Back](https://hackaday.io/contest/184555-supplyframe-designlab-2022-hackaday-prize/log/204306-challenge-3-hack-it-back)
    * [Climate Resilient Communities](https://hackaday.io/contest/184555-supplyframe-designlab-2022-hackaday-prize/log/204307-challenge-4-climate-resilient-communities)
    * [Save the World Wildcard](https://hackaday.io/contest/184555-supplyframe-designlab-2022-hackaday-prize/log/204308-challenge-5-save-the-world-wildcard)

## Hardware platforms
###### Existing resources for developing/deploying your own sustainability-focused hardware:
* [FieldKit](http://conservify.org/core-projects/fieldkit): Open source hardware AND software tools for field research / citizen science and sharing data
* [Microsoft Project 15](https://microsoft.github.io/project15): Open platform for conservation and ecological sustainability solutions
* [ROS](https://www.ros.org) – Robot Operating System – not sustainability-focused, but an open and adaptable set of resources for robotics

## Certifications / guidelines
* [ROHS certification](https://www.rohsguide.com/rohs-faq.htm): Restriction of Hazardous Substances
* [Open Source Hardware Association (OSHWA) certification](https://certification.oshwa.org)
* [TCO Certification](https://tcocertified.com/criteria-overview/): "Criteria are comprehensive and cover both environmental and social responsibility in the supply chain and throughout the IT product life cycle."
* [B Corporations](https://www.bcorporation.net/en-us/)
* iFixit's [consumer electronics repairability scores](https://www.ifixit.com/Right-to-Repair/Repairable-Products)

## More resources
* [ClimateAction.tech](http://ClimateAction.tech) – Community focusing on:
    * Business culture & behavior change
    * Green software engineering
    * Sustainable product design (!!)
    * Low-carbon infrastructure
    * Also, CAT's _Branch_ Magazine: [Design options for sustainable hardware and software](https://branch.climateaction.tech/issues/issue-2/design-options-for-sustainable-hardware-and-software)
* [Fairphone](https://www.fairphone.com/en/impact): Notes on product longevity, circularity, fair materials, and good working conditions
* [Project Drawdown](https://www.drawdown.org/solutions): Thoroughly researched and ranked solutions for the climate crisis, from technology ([building automation systems](https://www.drawdown.org/solutions/building-automation-systems)) to culture ([carpooling](https://www.drawdown.org/solutions/carpooling)). Filter by "electricity" for those most relevant to our niche.
* [UN Sustainable Development Goals](https://www.undp.org/sustainable-development-goals)
* Some info on [Germany's environmental policies](https://earth911.com/business-policy/recycling-in-germany) putting the onus on companies to provide recycling for their products and packaging
* [UL whitepaper](https://github.com/alexglow/green-ee/wiki/UL-whitepaper): [Verifying Environmental Sustainability in the Electronics Marketplace](https://www.ul.com/insights/verifying-environmental-sustainability-electronics-marketplace)