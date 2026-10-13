# Upstream Petroleum Domain Reference

## 1. Upstream Petroleum Lifecycle

### 1.1 Exploration

- **Physical Objective**: Locate commercial hydrocarbon accumulations trapped in sedimentary rock.
    
- **Core Operations**: Gravimetric and magnetometric surveys followed by 2D/3D seismic reflection surveys. If viable prospects are mapped, a wildcat exploration well is drilled.
    
- **Subsurface Imaging**: Is the process of creating images of underground geological formations to identify potential oil and gas reservoirs, faults, rock layers, and geological structures.
    
- **Key Deliverables**:
    
    - **2D/3D Seismic Images**: Visual representations of subsurface geological formations.
        
    - **Structural Interpretation Maps**: Maps identifying faults, folds, and geological traps.
        
    - **Horizon Maps**: Surfaces representing geological boundaries and potential reservoir layers.
        
    - **Depth Maps**: Estimated depths of target formations and potential reservoirs.
        
    - **Velocity Models**: Models of seismic-wave velocities used for accurate subsurface imaging and depth conversion.
        
    - **Prospect Maps**: Identification of potential hydrocarbon accumulation locations for exploration drilling.
        
    - **Seismic Data Files (SEG-Y)**: Raw and processed seismic traces used for imaging and geological interpretation.
        
    - **Well Logging Data (LAS/DLIS)**: Measurements of gamma ray, resistivity, porosity, and sonic properties used to evaluate formations.
        
    - **Exploration Report**: Integrated geological and geophysical interpretation assessing reservoir potential and drilling targets.
        

### 1.2 Drilling & Well Completion

- **Drilling Rig & Operations**: A drilling rig rotates a drill bit to penetrate subsurface formations.
    
- **Drilling Fluid Mechanics (Mud Weight & Pressure Balance)**: Drilling fluid density generates hydrostatic pressure to control formation fluids. Mud weight must be managed within the operational pressure window between pore pressure and fracture pressure to minimize kicks, lost circulation, and blowouts.
    
- **Casing Architecture**:
    
    - **Conductor Casing**: Stabilizes the shallow borehole and supports the initial drilling system.
        
    - **Surface Casing**: Protects freshwater aquifers and provides a foundation for well-control equipment.
        
    - **Intermediate Casing**: Isolates unstable formations, abnormal-pressure zones, and challenging intervals.
        
    - **Production Casing**: Provides structural integrity and isolates the production interval from surrounding formations.
        
- **Well Completion**:
    
    - **Perforation**: Creates flow pathways through the production casing and cement sheath into the target reservoir.
        
    - **Production Tubing**: Provides a dedicated conduit for transporting hydrocarbons from the reservoir to the surface.
        
    - **Wellhead & Christmas Tree**: Provides pressure containment, well access, and production-flow control through surface valves and fittings.
        

### 1.3 Production & Reservoir Management

- **Primary Recovery Mechanisms**: Production driven by natural reservoir energy, including water influx, gas-cap expansion, and solution-gas expansion. Production declines as reservoir pressure decreases and fluid-flow resistance increases.
    
- **Artificial Lift Systems**: Technologies used to increase or sustain production when natural reservoir energy is insufficient to transport fluids to the surface.
    
    - **Electric Submersible Pump (ESP)**: A downhole multistage centrifugal pump powered by an electric motor that increases fluid pressure and lifting capacity.
        
    - **Sucker Rod Pump (Mechanical Lift)**: A reciprocating downhole pump driven by a surface pumping unit to lift fluids through the production tubing.
        
    - **Gas Lift**: Injects high-pressure gas into the production tubing or annulus to reduce the effective density of the fluid column and improve flow.
        
- **Secondary & Tertiary Recovery (EOR)**:
    
    - **Secondary Recovery**: Waterflooding or gas injection to maintain reservoir pressure and displace hydrocarbons toward production wells.
        
    - **Tertiary Recovery / Enhanced Oil Recovery (EOR)**: Methods such as thermal injection, chemical flooding, and miscible gas injection to mobilize additional hydrocarbons and improve recovery.
        
- **Surface Separation (Oil / Gas / Water)**: Production fluids enter separators that divide the well stream into oil, gas, and produced water for measurement, treatment, storage, reinjection, or disposal.
    

### 1.4 Abandonment (Plug & Abandonment - P&A)

- **Decommissioning Objectives**: Safely retire a well that has reached the end of its economic life or is no longer required, in accordance with applicable regulations and the approved abandonment program.
    
- **Zonal Isolation & Cement Plugs**: Install cement plugs and, where required, mechanical barriers across selected intervals to isolate hydrocarbon-bearing formations, protect groundwater, and prevent communication between geological zones. Verify barrier integrity using approved testing and verification methods.
    
- **Environmental Remediation**: Remove or secure surface equipment, manage contaminated soil and waste, restore the site, and meet applicable land or seabed restoration requirements.
---

## 2. Fundamental Reservoir Rock & Fluid Properties

### 2.1 Porosity ($\phi$)

- **Definition**: The fraction of a rock's total bulk volume occupied by pore spaces that can store fluids such as oil, gas, and water.
    
- **Formula**:
    
    $$\phi = \frac{V_{\text{pore}}}{V_{\text{bulk}}}$$
    
    Expressed as a percentage:
    
    $$\phi(\%) = \frac{V_{\text{pore}}}{V_{\text{bulk}}} \times 100$$
    
    Where:
    
    - $V_{\text{pore}}$ = Total pore volume.
    - $V_{\text{bulk}}$ = Total bulk volume of the rock, including solids and pores.
    - $\phi$ = Porosity (dimensionless fraction).
        
- **Typical Field Ranges**:
    
    - **Low / Tight Porosity**: Less than 5%.
    - **Moderate Porosity**: 5–15%.
    - **Good Porosity**: 15–25%.
    - **High Porosity**: Greater than 25%.
        
    *Note*: Actual porosity depends on lithology, compaction depth, cementation, and diagenetic history.
    

### 2.2 Permeability ($k$)

- **Definition**: A measure of a porous rock's ability to transmit fluids through interconnected pore networks. Permeability is an intrinsic geometric property of the rock pore throat distribution.
    
- **Darcy's Law Formulations**:
    
    **1. Fundamental SI Formulation (Linear Laminar Flow):**
    
    $$q = -\frac{k A}{\mu} \frac{\Delta P}{L} = \frac{k A}{\mu} \frac{P_{\text{in}} - P_{\text{out}}}{L}$$
    
    Where:
    - $q$ = Volumetric flow rate ($\text{m}^3/\text{s}$).
    - $k$ = Absolute permeability ($\text{m}^2$).
    - $A$ = Cross-sectional area perpendicular to flow ($\text{m}^2$).
    - $\mu$ = Dynamic viscosity of the fluid ($\text{Pa}\cdot\text{s}$).
    - $\Delta P$ = Pressure differential ($P_{\text{out}} - P_{\text{in}}$) ($\text{Pa}$).
    - $L$ = Length of the porous medium ($\text{m}$).
    - The negative sign indicates flow occurs from higher pressure to lower pressure ($P_{\text{in}} > P_{\text{out}}$).

    **2. Petroleum Engineering Field Units Formulation:**
    In oilfield operations, Darcy's Law incorporates the standard imperial conversion factor $0.001127$:
    
    $$q = 0.001127 \frac{k A}{\mu} \frac{\Delta P}{L}$$
    
    Where:
    - $q$ = Flow rate ($\text{STB/day}$ or $\text{BBL/day}$).
    - $k$ = Permeability ($\text{mD}$, millidarcies).
    - $A$ = Cross-sectional area ($\text{ft}^2$).
    - $\mu$ = Dynamic viscosity of the fluid ($\text{cP} = \text{centipoise}$).
    - $\Delta P$ = Pressure drop across interval ($\text{psi}$).
    - $L$ = Drainage or flow length ($\text{ft}$).
    - $0.001127$ = Darcy-to-Field conversion constant ($\frac{1\ \text{Darcy} \times 86400\ \text{s/day} \times 1\ \text{psi/ft}}{14.696\ \text{psi/atm} \times 30.48\ \text{cm/ft} \times 158987.3\ \text{cm}^3/\text{bbl}}$).

- **Units & Conversions**:
    
    - **SI Unit**: Square meter ($\text{m}^2$).
    - **Darcy (D)**: Standard unit in porous media fluid dynamics ($1\ \text{D} = 1000\ \text{mD}$).
    - **Millidarcy (mD)**: Working oilfield unit ($10^{-3}\ \text{D}$).
    
    Conversion factors:
    
    $$1\ \text{D} \approx 9.86923 \times 10^{-13}\ \text{m}^2$$
    
    $$1\ \text{mD} = 10^{-3}\ \text{D} \approx 9.86923 \times 10^{-16}\ \text{m}^2$$
    

### 2.3 Fluid Saturation ($S_o, S_g, S_w$)

- **Definition**: The fraction of the rock's interconnected pore volume ($V_{\text{pore}}$) occupied by a specific fluid phase.
    
    - $S_o$ = Oil saturation.
    - $S_g$ = Gas saturation.
    - $S_w$ = Water saturation.
        
- **Formula**:
    
    $$S_o = \frac{V_o}{V_{\text{pore}}}, \quad S_g = \frac{V_g}{V_{\text{pore}}}, \quad S_w = \frac{V_w}{V_{\text{pore}}}$$
    
    Where:
    - $V_o$ = Volume of oil in the pore space.
    - $V_g$ = Volume of free gas in the pore space.
    - $V_w$ = Volume of formation water in the pore space.
    - $V_{\text{pore}}$ = Total interconnected pore volume ($\phi \times V_{\text{bulk}}$).
        
- **Volumetric Closure Constraint**: The entire available pore space is occupied by the fluid phases, so saturations must sum to unity:
    
    $$S_o + S_g + S_w = 1$$
    
    Expressed as percentages:
    
    $$S_o(\%) + S_g(\%) + S_w(\%) = 100\%$$
    
    **Field Example**: If an Orinoco belt or conventional reservoir core reveals $S_o = 0.60$ (60% oil) and $S_w = 0.25$ (25% formation water), the remaining free gas saturation is:
    
    $$S_g = 1 - (S_o + S_w) = 1 - (0.60 + 0.25) = 0.15 \quad (15\%)$$
    
    *Significance*: Fluid saturations directly feed Volumetric Original Oil in Place (OOIP) calculations ($N = \frac{7758 \cdot A \cdot h \cdot \phi \cdot (1 - S_w)}{B_{oi}}$) and relative permeability curves.

---

## 3. Production Telemetry & Data Entities (Database Target Schema)

| Field Name | Physical Entity | Standard Units | Sensor / Source |
|---|---|---|---|
| `well_id` | Unique API/Well Identifier | String / UUID | Master Well Index |
| `date` | Production Date | YYYY-MM-DD | Daily Production Report |
| `oil_rate_bopd` | Oil Production Rate | BBL/day | 3-Phase Separator / Coriolis Meter |
| `gas_rate_mscfd` | Associated Gas Rate | MSCF/day | Orifice Meter / Gas Chromatograph |
| `water_rate_bwpd` | Produced Water Rate | BBL/day | Separator Water Meter |
| `water_cut_pct` | Water Cut (BS&W) | % | Lab Centrifuge / Water-Cut Monitor |
| `wellhead_pressure_psi` | Tubing Head Pressure ($P_{wh}$) | psig | Surface Pressure Transducer |
| `bottomhole_pressure_psi`| Flowing Bottomhole Pressure ($P_{wf}$) | psig | Downhole Gauge / Permanent Gauge |
| `choke_size_64ths` | Wellhead Choke Orifice Size | 1/64 inch | Production Choke Manifold |
