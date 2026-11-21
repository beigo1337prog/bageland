## Iron and steel

Steel only comes from the full steelworks chain. Each step is worth more than its ingredients:
1. **Crusher**: iron ore → crushed iron ×2. **Ore Washer**: crushed iron + water → iron concentrate.
2. **Coke Oven**: coal ×3 → coke ×2. **Limestone Quarry** supplies limestone.
3. **Blast Furnace** (8×8): concentrate ×5 + coke ×3 + limestone ×2 → 50 hot metal (molten pig iron, fluid pipe) + 3 slag (items), every 4 s. Both outputs must be carried away or it stops. Each batch adds 1 pollution.
4. **Electrolyzer**: water → oxygen. **Oxygen Converter**: 40 hot metal + 10 oxygen → 40 molten steel.
5. **Caster**: molten steel → steel ingot or steel slab (pin the recipe you want). **Rolling Mill**: steel slab → 3 steel plates.
6. The rolling mill also rolls slabs into steel beams, and the machine shop turns ingots, plates and beams into parts (see below).
7. **Slag → building materials**: the **Cement Kiln** (6×3): limestone ×3 + slag ×2 (or gypsum ×2) + coal → cement ×3. The **Concrete Mixer** (3×3): cement ×2 + sand ×2 + 10 water → concrete ×2. The **Precast Yard** (5×4): concrete ×6 + steel beam → precast girder. Unlocked by **Cement** (after Quarrying and Ironmaking) and **Precast Concrete** (after Cement and Rolling).

Early iron, copper and glass go through two steps: the **Furnace** melts ore + coal into 2 molten iron or molten copper (crushed ore melts faster), or 2 sand + coal into 2 molten glass, sent out through a fluid pipe; the **Ingot Molder** (3×2) casts 2 melt into an ingot (or a piece of glass). Furnace melt is not hot metal: only the blast furnace's carbon-rich hot metal goes to the converter.

## Copper

Refined copper comes from the copper works; the furnace and ingot molder still turn copper ore into ingots for early money.
1. **Crusher**: copper ore → crushed copper ×2. **Flotation Cell**: crushed copper ×2 + water → copper concentrate ×2.
2. **Flash Smelter** (8×7): concentrate ×4 + sand + 10 oxygen → 40 copper matte (fluid pipe) + 2 slag (items).
3. **Copper Converter**: 40 matte + 10 oxygen → 40 blister copper + 20 sulfur dioxide (both fluid pipes; both must be taken away).
4. **Caster**: 20 blister copper → copper anode. **Acid Plant**: 20 sulfur dioxide + 10 water → 10 sulfuric acid; or 10 sulfuric acid + 10 water + 2 fluorite → 10 hydrofluoric acid + 1 gypsum. Fluorite comes from the **Fluorite Quarry** (research Fluorite Mining) on rare deposits far from the start.
5. **Electrorefinery**: copper anode + 5 sulfuric acid → copper cathode.
6. **Rolling Mill**: cathode → copper rod ×2. **Component Manufacturer**: rod → copper wire ×30 (an ingot gives 2). **Assembler**: wire ×4 + plastic → copper cable, or wire ×8 + nylon → copper cable ×2.
7. **Rolling Mill**: cathode → copper foil ×3, for circuit boards.

## Oil and plastics

1. **Distillation Tower** (5×7): 40 crude oil → 20 naphtha + 10 fuel oil (both fluid pipes; both must be taken away).
2. **Steam Cracker** (6×4): 20 naphtha + 10 water → 20 ethylene + 10 hydrogen (both fluid pipes).
3. **Polymer Reactor** (5×5): 20 ethylene + 5 hydrogen → plastic ×2 (the hydrogen sets how long the polymer chains grow). **Injection Molder**: plastic ×2 → plastic casing, or nylon ×2 → nylon gears ×3. The Polymer Reactor also makes photoresist: 10 benzene + 5 ethylene → photoresist ×2.
4. Fuel oil runs the **Oil Generator**; hydrogen feeds the polysilicon reactor.

Nearly every refining step also leaves **Heavy Residue** (4 from distilling, 2 from steam cracking and reforming). It goes to:
1. **Vacuum Tower** (5×7): 10 residue → 5 gas oil + 1 lube oil + 3 residue.
2. **Catalytic Cracker** (5×6): 20 gas oil → 14 gasoline + 2 residue.
3. **Hydrotreater** (5×5): 20 fuel oil + 5 hydrogen → 16 diesel + 1 sulfur (solid) + 2 residue.
4. **Delayed Coker** (4×6): 20 residue → 2 petroleum coke (solid) + 6 gas oil, every 8 s. Petroleum coke fires a **Fired Heater** like coke (smoke 0.8).
5. **Asphalt Plant** (4×4): 5 residue + 2 sand → 2 asphalt; or 5 fuel oil + 9 ammonium nitrate → 2 ANFO (mining explosive).

Research: Vacuum Distillation, Delayed Coking and Asphalt (after Distillation), Catalytic Cracking (after Vacuum Distillation), Hydrotreating (after Steam Cracking, for its hydrogen).

## Chemicals

The endgame chemical works build on the refinery and the electrolyzer:
1. **Catalytic Reformer** (5×5): 20 naphtha → 10 benzene + 10 hydrogen.
2. **Air Separation Unit** (5×4): 5 cooling water → 20 nitrogen + 5 oxygen.
3. **Ammonia Converter** (5×5): 10 nitrogen + 30 hydrogen → 20 ammonia.
4. **Nitric Acid Plant** (5×4): 10 ammonia + 20 oxygen → 10 nitric acid.
5. **Prilling Tower** (4×6): 10 ammonia + 10 nitric acid → 2 ammonium nitrate (fertilizer).
6. **Nylon Plant** (7×6): 20 benzene + 10 hydrogen + 10 nitric acid + 10 ammonia → 2 nylon.

Research: Catalytic Reforming (after Distillation), Air Separation (after Electrolysis), Ammonia Synthesis, Nitric Acid, Fertilizer and Nylon.

## Electronics

1. **Smelter**: sand ×2 + carbon dust → silicon. **Polysilicon Reactor** (5×5): silicon ×2 + 20 hydrogen → polysilicon (or the tier 6 Siemens route, below).
2. **Crystal Puller**: polysilicon ×2 + 10 nitrogen → silicon boule. **Wafer Saw**: boule + 10 water → wafers ×6.
3. **Chip Fab** (8×6): wafer + copper wire ×2 + 10 sulfuric acid + photoresist + 5 nitrogen → microchips ×4; with 10 hydrofluoric acid instead of the sulfuric acid → microchips ×6.
4. **PCB Laminator**: glass ×2 + plastic + copper foil → bare circuit board.
5. **Component Manufacturer**: bare board + microchip ×2 + copper wire ×2 → circuit board.
6. **Display Line**: glass ×2 + microchip + plastic → display.

## Machine parts and products

1. **Machining Center**: steel ingot → ball bearings ×2, or bolts ×8. **Stamping Press**: steel plate → laminations ×4.
2. **Coil Winder**: laminations ×4 + copper wire ×6 → stator.
3. **Assembler**: steel beam ×2 + steel plate ×2 + bolts ×6 → steel frame; stator + bearings ×2 + iron gears ×2 → electric motor; motor + bearings ×2 + plastic casing → air compressor.
4. **Advanced Assembler** (four inputs): circuit boards ×2 + display + casing → control panel (6 s); motor + circuit board + nylon gears ×2 → servo actuator (7 s); servo ×4 + control panel + steel frame + copper cable ×2 → industrial robot ($45,000); circuit boards ×4 + display + casings ×2 + copper cable → computer ($7,500).
