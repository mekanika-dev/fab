---
title: "USER MANUAL: CNC FAB"
css: style.css
---

<div class="cover-page" style="text-align: center;">

<img src="Media/Logo Mekanika.png" alt="Logo Mekanika" style="max-width: 350px; margin-top:100px">

<h4 style="margin-bottom: 0;">3-AXIS CNC MILLING MACHINE</h4>

<hr style="width: 200px; margin: 10px auto; color:#000 !important;"/>

<h4 style="margin-top: 0;">FAB MODEL V1.0</h4>

<img src="Media/Fab ISO View.png" alt="Fab ISO View" style="max-width: 500px; margin-top:50px; margin-bottom:25px;">

**ORIGINAL MANUAL**
<br/>
Version: 1.0.0-EN
<br/>
Revision Date: November 2025

</div>

<div class="page-break"></div>

## TABLE OF CONTENTS

#### 1. GENERAL INFORMATION

<ul style="list-style-type: none;">
  <li>1.1 <a href="#11-manufacturer-identification">Manufacturer identification</a></li>
  <li>1.2 <a href="#12-ce-declaration-of-conformity">CE Declaration of Conformity</a></li>
  <li>1.3 <a href="#13-intended-use">Intended use</a>
    <ul style="list-style-type: none;">
      <li>1.3.1 <a href="#131-normal-use">Normal Use</a></li>
      <li>1.3.2 <a href="#132-prohibited-uses">Prohibited uses</a></li>
    </ul>
  </li>
  <li>1.4 <a href="#14-authorized-personnel">Authorized personnel</a>
    <ul style="list-style-type: none;">
      <li>1.4.1 <a href="#141-minimum-requirements">Minimum requirements</a></li>
      <li>1.4.2 <a href="#142-restrictions">Restrictions</a></li>
    </ul>
  </li>
</ul>

#### 2. SAFETY

<ul style="list-style-type: none;">
  <li>2.1 <a href="#21-safety-instructions-by-risk-level">Safety instructions by risk level</a></li>
  <li>2.2 <a href="#22-personal-protective-equipment">Personal protective equipment</a>
    <ul style="list-style-type: none;">
      <li>2.2.1 <a href="#221-mandatory-ppe">Mandatory PPE</a></li>
      <li>2.2.2 <a href="#222-dress-code">Dress Code</a></li>
    </ul>
  </li>
  <li>2.3 <a href="#23-safety-devices">Safety devices</a>
    <ul style="list-style-type: none;">
      <li>2.3.1 <a href="#231-emergency-stop">Emergency stop</a></li>
      <li>2.3.2 <a href="#232-limit-switches">Limit switches</a></li>
      <li>2.3.3 <a href="#233-dust-shoe">Dust shoe</a></li>
    </ul>
  </li>
</ul>

#### 3. TECHNICAL DESCRIPTION

<ul style="list-style-type: none;">
  <li>3.1 <a href="#31-overview">Overview</a>
    <ul style="list-style-type: none;">
      <li>3.1.1 <a href="#311-axis-diagram">Axis diagram</a></li>
      <li>3.1.2 <a href="#312-control-box-diagram">Control box diagram</a></li>
    </ul>
  </li>
  <li>3.2 <a href="#32-technical-specifications">Technical specifications</a></li>
</ul>

#### 4. INSTALLATION & ASSEMBLY

<ul style="list-style-type: none;">
  <li>4.1 <a href="#41-unpacking-and-inspection">Unpacking and inspection</a>
    <ul style="list-style-type: none;">
      <li>4.1.1 <a href="#411-upon-receipt">Upon receipt</a></li>
      <li>4.1.2 <a href="#412-kit-inventory">Kit inventory</a></li>
    </ul>
  </li>
  <li>4.2 <a href="#42-assembly">Assembly</a>
    <ul style="list-style-type: none;">
      <li>4.2.1 <a href="#421-preparation">Preparation</a></li>
    </ul>
  </li>
  <li>4.3 <a href="#43-installation">Installation</a>
    <ul style="list-style-type: none;">
      <li>4.3.1 <a href="#431-recommended-layout">Recommended layout</a></li>
      <li>4.3.2 <a href="#432-room-requirements">Room requirements</a></li>
    </ul>
  </li>
</ul>

#### 5. INITIAL STARTUP

<ul style="list-style-type: none;">
  <li>5.1 <a href="#51-preliminary-checks">Preliminary checks</a>
    <ul style="list-style-type: none;">
      <li>5.1.1 <a href="#511-safety-checklist">Safety checklist</a></li>
    </ul>
  </li>
  <li>5.2 <a href="#52-first-power-on">First power-on</a>
    <ul style="list-style-type: none;">
      <li>5.2.1 <a href="#521-startup-sequence">Startup sequence</a></li>
    </ul>
  </li>
  <li>5.3 <a href="#53-functional-test">Functional test</a></li>
</ul>

#### 6. OPERATION

<ul style="list-style-type: none;">
  <li>6.1 <a href="#61-checklist-for-safe-machine-operation">Checklist for safe machine operation</a>
    <ul style="list-style-type: none;">
      <li>6.1.1 <a href="#611-daily-startup">Daily startup</a></li>
    </ul>
  </li>
  <li>6.2 <a href="#62-workpiece-clamping">Workpiece clamping</a>
    <ul style="list-style-type: none;">
      <li>6.2.1 <a href="#621-clamping-systems-supplied-with-base-kit">Clamping systems supplied with base kit</a></li>
      <li>6.2.2 <a href="#622-clamping-rules">Clamping rules</a></li>
    </ul>
  </li>
  <li>6.3 <a href="#63-tool-installation">Tool installation</a>
    <ul style="list-style-type: none;">
      <li>6.3.1 <a href="#631-tool-change">Tool change</a></li>
      <li>6.3.2 <a href="#632-tool-length-measurement">Tool length measurement</a></li>
    </ul>
  </li>
  <li>6.4 <a href="#64-programming-and-machining">Programming and machining</a>
    <ul style="list-style-type: none;">
      <li>6.4.1 <a href="#641-accepted-formats">Accepted formats</a></li>
      <li>6.4.2 <a href="#642-operating-modes">Operating modes</a></li>
    </ul>
  </li>
  <li>6.5 <a href="#65-monitoring-during-machining">Monitoring during machining</a>
    <ul style="list-style-type: none;">
      <li>6.5.1 <a href="#651-check-points">Check points</a></li>
      <li>6.5.2 <a href="#652-anomalies-and-actions">Anomalies and actions</a></li>
    </ul>
  </li>
</ul>

#### 7. ADD-ONS AND OPTIONS

<ul style="list-style-type: none;">
  <li>7.1 <a href="#71-vacuum-table">Vacuum table</a>
    <ul style="list-style-type: none;">
      <li>7.1.1 <a href="#711-specifications">Specifications</a></li>
      <li>7.1.2 <a href="#712-use">Use</a></li>
    </ul>
  </li>
  <li>7.2 <a href="#72-dust-collection-kit">Dust collection kit</a>
    <ul style="list-style-type: none;">
      <li>7.2.1 <a href="#721-specifications">Specifications</a></li>
    </ul>
  </li>
  <li>7.3 <a href="#73-laser-module-lsr">Laser module (LSR)</a>
    <ul style="list-style-type: none;">
      <li>7.3.1 <a href="#731-specifications">Specifications</a></li>
    </ul>
  </li>
</ul>

#### 8. MAINTENANCE & TROUBLESHOOTING

<ul style="list-style-type: none;">
  <li>8.1 <a href="#81-preventive-maintenance-plan">Preventive maintenance plan</a></li>
  <li>8.2 <a href="#82-lubrication">Lubrication</a></li>
  <li>8.3 <a href="#83-spare-parts">Spare parts</a></li>
</ul>

#### 9. TROUBLESHOOTING

<ul style="list-style-type: none;">
  <li>9.1 <a href="#91-troubleshooting-and-diagnostics">Troubleshooting and diagnostics</a></li>
  <li>9.2 <a href="#92-technical-support">Technical support</a>
    <ul style="list-style-type: none;">
      <li>9.2.1 <a href="#921-before-contacting-support">Before contacting support</a></li>
    </ul>
  </li>
</ul>

#### 10. TRANSPORTATION & STORAGE

<ul style="list-style-type: none;">
  <li>10.1 <a href="#101-machine-transportation">Machine Transportation</a></li>
  <li>10.2 <a href="#102-packaging--waste">Packaging & Waste</a></li>
  <li>10.3 <a href="#103-storage">Storage</a></li>
</ul>

## 1. GENERAL INFORMATION {#1-general-information}

### 1.1 Manufacturer identification {#11-manufacturer-identification}

**Mekanika SRL**

Chaussée de Mons 1281  
1070 Anderlecht, Belgium  
VAT No.: BE0740501760

**Contact:**

<ul style="list-style-type: none;">
<li><i class="fas fa-envelope" style="color: #2196f3;"></i> info@mekanika.io</li>
<li><i class="fas fa-globe" style="color: #2196f3;"></i> www.mekanika.io</a></li>
</ul>

### 1.2 CE Declaration of Conformity {#12-ce-declaration-of-conformity}

This machine complies with the following European directives:

- **2006/42/EC** - Machinery Directive
- **2014/30/EU** - Electromagnetic Compatibility (EMC) Directive

**Harmonized standards applied:**

- **EN ISO 12100:2010** - Safety of machinery, General principles
- **EN 60204-1:2006** - Electrical safety of machinery
- **EN ISO 13850:2015** - Emergency stop function
- **EN 848-3:2012** - Safety of woodworking machines (partially)
- **EN 61000-6-1** - EMC Immunity
- **EN 61000-6-3** - EMC Emissions

The original declaration of conformity is supplied with this machine.

### 1.3 Intended use {#13-intended-use}

Please read this instruction manual and all accompanying documents in their entirety before commissioning the machine.

If in doubt or if you need additional information, please do not hesitate to contact us before using the machine.

#### 1.3.1 Normal Use {#131-normal-use}

The MEKANIKA FAB CNC milling machine is a 3-axis CNC machine intended for:

<ul style="list-style-type: none; margin-left: 0.75em">
  <li><i class="fas fa-square-check" style="color: #4EBD7D;"></i> Machining of wood and derivatives (plywood, MDF, OSB)</li>
  <li><i class="fas fa-square-check" style="color: #4EBD7D;"></i> Machining of plastics (PVC, acrylic, polycarbonate)</li>
  <li><i class="fas fa-square-check" style="color: #4EBD7D;"></i> Machining of non-ferrous metals (aluminum, brass)</li>
  <li><i class="fas fa-square-check" style="color: #4EBD7D;"></i> Machining of composite materials (with special precautions)</li>
</ul>

#### 1.3.2 Prohibited uses {#132-prohibited-uses}

The following uses are **PROHIBITED:**

<ul style="list-style-type: none; margin-left: 0.75em">
  <li><i class="fas fa-xmark" style="color: #d32f2f;"></i> Machining of unknown composite materials or materials containing asbestos</li>
  <li><i class="fas fa-xmark" style="color: #d32f2f;"></i> Use in explosive atmospheres</li>
  <li><i class="fas fa-xmark" style="color: #d32f2f;"></i> Outdoor or humid environment use</li>
  <li><i class="fas fa-xmark" style="color: #d32f2f;"></i> Machining of improperly secured workpieces</li>
  <li><i class="fas fa-xmark" style="color: #d32f2f;"></i> Machining beyond the machine's technical capabilities</li>
</ul>

### 1.4 Authorized personnel {#14-authorized-personnel}

#### 1.4.1 Minimum requirements {#141-minimum-requirements}

- **Minimum age:** 16 years
- **Required training:**
  - Complete reading of this manual
  - Completed online training (series of free video tutorials)
  - Basic CAM knowledge
- **Physical abilities:**
  - Normal or corrected vision
  - Normal or aided hearing
  - Sufficient mobility to access the emergency stop

#### 1.4.2 Restrictions {#142-restrictions}

- Prohibition for untrained persons
- Prohibition for persons under the influence (alcohol, drugs, medication)
- Mandatory supervision for persons learning on the machine

## 2. SAFETY {#2-safety}

Read the entire user manual to familiarize yourself with the machine's features and how to use them. Incorrect operation of the machine can result in damage to the machine, your personal property and cause serious injury, electric shock and/or fire.

**It is imperative to comply at all times with the safety instructions listed in this operating manual.**

### 2.1 Safety instructions by risk level {#21-safety-instructions-by-risk-level}

The following terms are used in this user manual to indicate different levels of potential danger when using this machine. The safety symbols and their explanations require your attention.

Safety warnings do not eliminate any danger. The instructions or warnings they give are not a substitute for appropriate preventive measures.

> **<i class="fas fa-ban" style="color: #d32f2f;"></i> DANGER** - _Instructions which, if not properly followed, create a probability of property damage, collateral damage, serious injury or death or create a high probability of minor injury._

| **TYPE OF RISK**                      | **SAFETY INSTRUCTIONS**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| :------------------------------------ | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Risk of electrocution**             | Machine plugs must match the power outlet used. Never modify the plug in any way. Do not use adapter plugs with grounded machines.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| **Risk of electrocution - indirect contact** | An insulation fault can energize normally non-conductive metal parts (chassis, structure, housing). Causes include: cable wear in cable chains, moisture infiltration, accumulation of conductive dust, failing components, or mechanical damage. Never use the machine if: <br/> - The circuit breaker trips repeatedly; <br/> - Traces of electrical arcing are visible (blackening, burning smell); <br/> - Moisture/condensation is visible in the housing.                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| **Toxic dust**                        | Some dusts created when machining certain types of materials may contain chemicals known to cause cancer, birth defects or other reproductive harm. Always research the material you are working with before machining it. Examples of these chemicals include: lead from non-ferrous metals containing lead, carbonate from carbon fiber, arsenic and chromium from chemically treated wood.<br><br>The risk you face from exposure varies depending on how often you perform this type of work. To reduce your exposure to these chemicals: work in a well-ventilated area and use approved safety equipment, such as dust masks specifically designed to filter microscopic particles. |
| **Explosive atmosphere**              | Do not operate the machine in explosive atmospheres, such as in the presence of flammable liquids, gases or dusts. Machines can create sparks which may ignite dusts or fumes.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |

> **<i class="fas fa-exclamation-triangle" style="color: #ff9800;"></i> WARNING** - _Instructions which, if not properly followed, create a probability of property damage and a possibility of serious injury._

| **TYPE OF RISK**             | **SAFETY INSTRUCTIONS**                                                                                                                                                                                                                                             |
| :--------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Clothing**                 | Dress appropriately. Do not wear loose clothing or jewelry. Pin your hair above your shoulders so it cannot get caught in linear guides or moving parts.                                                                                                            |
| **Vigilance**                | Stay alert, watch what you are doing and use common sense when operating a machine. Do not use a machine when you are tired and/or under the influence of drugs, alcohol or medication. A moment of inattention while using a machine can result in serious injury. |
| **Personal protection**      | Use personal protective equipment. Always wear eye protection. Protective equipment such as a dust mask or appropriate hearing protection reduces the risk of injury.                                                                                               |
| **Machine control**          | This machine is controlled by a computer. During operation, it cannot be controlled directly. Lack of caution or expertise as well as program errors can result in unexpected movements.                                                                            |
| **Rotating tool**            | Do not touch the rotating tool area. The proximity of the rotating tool to your hand is not always obvious.                                                                                                                                                         |
| **Tool blocking**            | If the workpiece or end mill becomes blocked, immediately press the emergency stop button. Wait for all moving parts to stop and for the spindle to be turned off, then free the jammed material. Do not attempt to do this while the spindle is running.           |
| **Hot tools**                | Do not touch the end mill or collet after use. After use, they are too hot to touch with bare hands.                                                                                                                                                                |
| **Hot surfaces**             | Do not touch the motors, as they can heat up during machine operation.                                                                                                                                                                                              |
| **Tool handling**            | Be careful when handling tools, they can be very sharp. Never place any part of the tool or accessories in your mouth, as this can result in serious injury.                                                                                                        |
| **Workpiece clamping**       | Before starting any machining operation, always firmly clamp your workpiece. Never try to hold the workpiece by hand or with accessories. These tools can easily jam in the material and can kick back, resulting in loss of control and serious injury.            |
| **Limit sensors**            | Never try to reach the limit sensors when the machine is in motion, this could result in crushing of your hand or fingers.                                                                                                                                          |
| **Prohibited modifications** | Do not modify your machine, or use it in a manner not intended by the manufacturer. Any alteration or modification constitutes misuse and may result in serious injury.                                                                                             |
| **Lockout**                  | Disconnect the plug from the power source before making adjustments, changing accessories or disassembling the machine.                                                                                                                                             |
| **Machine access**           | Keep the machine out of reach of children and do not allow persons unfamiliar with these instructions to use the machine. Machines are dangerous in the hands of untrained users.                                                                                   |
| **Safety distance**          | Keep children and bystanders at a distance. Distractions can cause you to lose control and cause accidents.                                                                                                                                                         |

> **<i class="fas fa-info-circle" style="color: #2196f3;"></i> CAUTION** - _Instructions which, if not properly followed, create a possibility of property damage and a possibility of minor injury._

| **TYPE OF RISK**             | **SAFETY INSTRUCTIONS**                                                                                                                                                                                                                                                                    |
| :--------------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Mandatory training**       | All persons who use the machine must have read and fully understood all relevant safety and operating instructions. Any misunderstanding can result in injury.                                                                                                                             |
| **Cleanliness and lighting** | Keep the work area clean and well lit. Cluttered or dark areas are conducive to accidents.                                                                                                                                                                                                 |
| **Indoor use**               | Only operate the machine in indoor spaces.                                                                                                                                                                                                                                                 |
| **Moisture protection**      | Do not expose the machine to moisture. The machine can only be used indoors.                                                                                                                                                                                                               |
| **Supervision**              | Do not leave the machine running unattended, and cut the spindle power if you leave. The machine is only secure when it is completely stopped and disconnected from the mains.                                                                                                             |
| **Proper use**               | Use the machine and its accessories in accordance with this manual, taking into account the working conditions and the work to be performed. Using the machine for operations other than those intended may result in a hazardous situation with a high probability of injury.             |
| **Tool condition**           | Never use dull or damaged end mills. Damaged end mills can break during use. Dull end mills require more force to cut, which can result in end mill breakage.                                                                                                                              |
| **Machining parameters**     | The speed and feed rate of the end mill during engraving, profiling or cutting are very important. Always observe the recommended speed and feed rate for a particular end mill/machine/operation configuration.                                                                           |
| **Ventilation**              | Remember to clean the ventilation openings of the control boxes using compressed air. Excessive dust accumulation inside the boxes can cause electrical failures.                                                                                                                          |
| **Preventive maintenance**   | Properly maintain the tools you use. Check for misalignment or binding of moving parts, broken parts and any other condition that may affect the operation of the machine. If damaged, have the machine repaired before using it. Many accidents are caused by poorly maintained machines. |
| **Repairs**                  | Have your machine repaired by a qualified technician using only identical replacement parts.                                                                                                                                                                                               |

### 2.2 Personal protective equipment {#22-personal-protective-equipment}

#### 2.2.1 Mandatory PPE {#221-mandatory-ppe}

| Equipment              | Use                                                               |                                 Pictogram                                 |
| :--------------------- | :---------------------------------------------------------------- | :-----------------------------------------------------------------------: |
| **Safety glasses**     | Recommended during machining                                      |   <img src="Media/ISO_7010_M004.png" alt="Safety glasses" width="50" />   |
| **Hearing protection** | Recommended during machining, mandatory if noise level > 80 dB(A) | <img src="Media/ISO_7010_M003.png" alt="Hearing protection" width="50" /> |
| **Gloves**             | Recommended when handling parts/tools                             |       <img src="Media/ISO_7010_M009.png" alt="Gloves" width="50" />       |
| **FFP2 mask**          | Mandatory when machining composite materials                      |     <img src="Media/ISO_7010_M016.png" alt="FFP2 mask" width="50" />      |
| **Safety shoes**       | Recommended for all work in front of a machine                    |    <img src="Media/ISO_7010_M008.png" alt="Safety shoes" width="50" />    |

#### 2.2.2 Dress Code {#222-dress-code}

**<i class="fas fa-square-check" style="color: #4EBD7D;"></i> MANDATORY:**

- Fitted clothing
- Short sleeves or rolled up
- Long hair tied back or under a cap

**<i class="fas fa-xmark" style="color: #d32f2f;"></i> PROHIBITED:**

- Jewelry (rings, necklaces, bracelets)
- Loose clothing
- Ties, scarves
- Gloves during machining

### 2.3 Safety devices {#23-safety-devices}

#### 2.3.1 Emergency stop {#231-emergency-stop}

**Characteristics:**

- Type: Lockable push button
- Color: Red on yellow background
- Standard: EN ISO 13850:2015
- Position: Front face, easily accessible

**Operation:**

1. **Activation:** Press the red button
   - Immediate stop of all movements
   - Spindle cutoff
   - Machine control software lockout
2. **Reset:** Turn the button clockwise
   - The program must be restarted manually

#### 2.3.2 Limit switches {#232-limit-switches}

**Configuration:**

- 6 NC PNP inductive sensors
- 2 sensors on X and Y axes (min/max) with AND logic for redundant safety

**Triple function:**

1. **Homing:** Machine referencing at startup
2. **Safety:** Emergency stop if limit reached
3. **Square gantry:** Gantry squaring

#### 2.3.3 Dust shoe {#233-dust-shoe}

**Dual function:**

- Protection against access to the tool
- Chip and dust extraction

> **<i class="fas fa-info-circle" style="color: #2196f3;"></i> CAUTION** - _Never remove the dust shoe during machining_

## 3. TECHNICAL DESCRIPTION {#3-technical-description}

### 3.1 Overview {#31-overview}

The MEKANIKA FAB is a 3-axis CNC milling machine, allowing material to be machined by moving along the X, Y and Z axes, or a combination of these by linear interpolation.

#### 3.1.1 Axis diagram {#311-axis-diagram}

<img src="Media/FAB Schema des axes.png" alt="Axis diagram" />

**Axis terminology:**

- **X axis:** Lateral movement (left-right)
- **Y axis:** Longitudinal movement (front-back)
- **Z axis:** Vertical movement (up-down)

#### 3.1.2 Control box diagram {#312-control-box-diagram}

<img src="Media/FAB Schema du boitier de controle.png" alt="Control box diagram" />

**Connector description:**

- **1**: Fan
- **2**: Motors
- **3**: Limit switches
- **4**: Emergency stop
- **5**: Tool probe (Input 1)
- **6**: Spindle control
- **7**: Input 2
- **8**: Input 3
- **9**: Laser control
- **10**: HDMI
- **11**: USB 2.0
- **12**: Ethernet
- **13**: Power supply
- **14**: Ground connection

### 3.2 Technical specifications {#32-technical-specifications}

| **CHARACTERISTIC**           | **VALUE**                            |
| :--------------------------- | :----------------------------------- |
| **MACHINE DIMENSIONS**       |                                      |
| Overall dimensions           | 1750 × 3150 × 1250 mm                |
| Total weight                 | 180 kg                               |
| **WORK AREA**                |                                      |
| Machinable surface           | 1330 x 2700 mm                       |
| Table-spindle distance (max) | 110 mm                               |
| **PERFORMANCE**              |                                      |
| Max travel speed             | 20000 mm/min                         |
| Recommended machining speed  | 100 - 10000 mm/min                   |
| **MECHANICS**                |                                      |
| Linear guides                | Double prismatic rail HGR20          |
| X & Z transmission           | Ball screws 16 mm (C7)               |
| Y transmission               | Double rack and pinion (Mod 2)       |
| Structure                    | Aluminum profiles + steel plates     |
| **MOTORS**                   |                                      |
| X & Y motors                 | NEMA34 6A                            |
| Z motors                     | NEMA23 5A                            |
| **SPINDLE**                  |                                      |
| Power                        | 2.2 kW                               |
| Cooling                      | Air                                  |
| Rotation speed               | 6000 - 24000 rpm                     |
| Collet                       | ER20 (1-13 mm)                       |
| Control                      | Variable frequency drive (VFD)       |
| **ELECTRICAL**               |                                      |
| Power supply                 | 230V AC single phase, 50 Hz          |
| Maximum power                | 3.5 kW                               |
| Protection                   | 16A fuse, mandatory grounding        |
| **ENVIRONMENT**              |                                      |
| Operating temperature        | 5°C to 35°C                          |
| Relative humidity            | 40-60%                               |
| Use                          | Indoor only                          |

## 4. INSTALLATION & ASSEMBLY {#4-installation--assembly}

### 4.1 Unpacking and inspection {#41-unpacking-and-inspection}

#### 4.1.1 Upon receipt {#411-upon-receipt}

**Check immediately:**

1. The condition of the packaging (photos if damaged)
2. The presence of all packages (see delivery note)
3. The absence of apparent damage

#### 4.1.2 Kit inventory {#412-kit-inventory}

We strongly recommend that you inventory your kit before starting assembly. The list of parts grouped by packaging is available on our website:

<br>
<i class="fas fa-globe" style="color: #2196f3;"></i> [support.mekanika.io/products/fab-cnc/kit-content](support.mekanika.io/products/fab-cnc/kit-content)

### 4.2 Assembly {#42-assembly}

Please carefully follow our online assembly guide to properly assemble your Mekanika machine.
<br>
<i class="fas fa-globe" style="color: #2196f3;"></i> [support.mekanika.io/products/fab-cnc/assembly-guide](support.mekanika.io/products/fab-cnc/assembly-guide)

#### 4.2.1 Preparation {#421-preparation}

- **Required space:** 3 × 4 m minimum
- **Estimated time:** 25 hours (alone) - 15 hours (2 people)
- **Required tools:** Provided in the kit

> **<i class="fas fa-exclamation-triangle" style="color: #ff9800;"></i> RISK** - There is a significant risk of heavy parts falling during assembly. Please handle heavy parts with a minimum of 2 people.

> **<i class="fas fa-info-circle" style="color: #2196f3;"></i> CAUTION** - Please follow the precise order of assembly steps to avoid risks of machine malfunction.

### 4.3 Installation {#43-installation}

#### 4.3.1 Recommended layout {#431-recommended-layout}

Place the machine on a level and stable floor. To ensure a comfortable working height, we recommend a working height of approximately 85 cm.

All moving parts of the machine must be able to operate without collision.

The machine must be easily accessible and usable. In particular, the emergency stop button must be easily accessible at all times.

**Zone description:**

- **1**: Operating zone
- **2**: Loading zone
- **3**: Maintenance and safety zone

<img src="Media/FAB Zone de travail.png" alt="Work area" />

#### 4.3.2 Room requirements {#432-room-requirements}

**Floor:**

- Flatness: < 5 mm/m
- Capacity: > 200 kg/m²
- Type: Concrete recommended

**Environment:**

- Temperature: 18-25°C ideal
- Humidity: 40-60%
- Lighting: > 500 lux on work area
- Ventilation: Adequate air renewal

## 5. INITIAL STARTUP {#5-initial-startup}

Before commissioning, the machine and all connected components must be properly wired and in perfect condition.

The operator must have read and understood the complete documentation of the relevant machine model and corresponding instructions. In addition, they must have been trained in the operation of the machine and its accessories and must be familiar with the use of the CNC milling machine and PlanetCNC software in general.

### 5.1 Preliminary checks {#51-preliminary-checks}

> **<i class="fas fa-info-circle" style="color: #2196f3;"></i> CAUTION** - Never power on before these checks

#### 5.1.1 Safety checklist {#511-safety-checklist}

**Mechanical:**

<ul style="list-style-type: none; margin-left: 0.75em">
  <li><i class="fas fa-square-check" style="color: #4EBD7D;"></i> Tightening of all fasteners</li>
  <li><i class="fas fa-square-check" style="color: #4EBD7D;"></i> Freedom of movement of axes (manual rotation)</li>
  <li><i class="fas fa-square-check" style="color: #4EBD7D;"></i> Absence of abnormal play</li>
  <li><i class="fas fa-square-check" style="color: #4EBD7D;"></i> Guides and ball screws lubricated</li>
</ul>

**Electrical:**

<ul style="list-style-type: none; margin-left: 0.75em">
  <li><i class="fas fa-square-check" style="color: #4EBD7D; "></i> Ground continuity (< 0.1 Ω)</li>
  <li><i class="fas fa-square-check" style="color: #4EBD7D;"></i> Cable insulation</li>
  <li><i class="fas fa-square-check" style="color: #4EBD7D;"></i> Tight connections</li>
  <li><i class="fas fa-square-check" style="color: #4EBD7D;"></i> Mains differential protection tested</li>
</ul>

**Safety:**

<ul style="list-style-type: none; margin-left: 0.75em">
  <li><i class="fas fa-square-check" style="color: #4EBD7D;"></i> Emergency stop accessible and functional</li>
  <li><i class="fas fa-square-check" style="color: #4EBD7D;"></i> Limit switches connected</li>
  <li><i class="fas fa-square-check" style="color: #4EBD7D;"></i> Dust shoe installed</li>
  <li><i class="fas fa-square-check" style="color: #4EBD7D;"></i> Work area clear</li>
</ul>

### 5.2 First power-on {#52-first-power-on}

#### 5.2.1 Startup sequence {#521-startup-sequence}

**1. Preparation**

- Clear area in front and around the machine
- PPE worn
- Documentation within reach

**2. Power-on**

- Check that emergency stop is unlocked
- Turn on control box
- Wait for Raspberry Pi initialization
- Wait for PlanetCNC to launch

**3. Initial checks**

- Control box fans rotating
- Limit switch indicators lit
- Touchscreen on and PlanetCNC interface active
- Emergency stop button functional

### 5.3 Functional test {#53-functional-test}

We strongly recommend following our illustrated machine startup guide, available on our website:
<br>
<i class="fas fa-globe" style="color: #2196f3;"></i> [support.mekanika.io/products/fab-cnc/get-started](https://support.mekanika.io/products/fab-cnc/get-started)

This includes all the necessary information to test the machine at first use, as well as useful information about its operation and safety features.

## 6. OPERATION {#6-operation}

The Fab CNC milling machine is intended for regular and professional use. Thanks to the rigidity of the machine, it is possible to process a variety of different materials, such as wood and non-ferrous metals.

The plausible and reasonable scope of uses includes:

- Manual movement mode, using a digital "jog" to move the machine along its 3 axes independently.
- The automatic positioning procedure, performed by the user by clicking a digital button. This procedure sequentially moves the machine on each of its axes in the following order: Z, X, Y, until it encounters the limit switches.
- The tool length measurement procedure, activated by the user by clicking a digital button. This procedure lowers the machine at reduced speed along its Z axis until its tool comes into contact with a removable sensor previously placed by the user.
- Normal operating mode, where the machine moves automatically according to a machine language, called G-code, previously loaded by the user.
- Manual control mode using a terminal allowing the machine to move according to a machine language, called G-code, entered directly by the user.

The plausible and reasonable scope of interventions includes:

- Manual movement of the machine to access certain areas.
- Calibration of the rack system using the compression spring.
- Tool change on the spindle.
- Attachment or removal of the dust shoe.
- Attachment or removal of material to be machined.
- Starting, pausing and stopping G-Code.
- Connection/disconnection of external machine cables.
- Opening cable chains to access the machine.

### 6.1 Checklist for safe machine operation {#61-checklist-for-safe-machine-operation}

#### 6.1.1 Daily startup {#611-daily-startup}

**1. Inspection and equipment**

- Inspect the equipment to ensure it has no obvious defects, damaged chucks, dull or cracked tools
- Use appropriate PPE (glasses, helmet,...)
- Tie back long hair and wear well-fitted clothing and roll up your sleeves to avoid snags

**2. Machine preparation**

- Check where the emergency stop button is located
- Never plug or unplug cables from the electronic box when the device is powered on
- Ensure the workpiece is firmly and securely clamped
- Check that the end mill is sharp and firmly tightened in the spindle chuck
- When handling or changing end mills, avoid touching the cutting edges
- Keep your hands free during manual adjustments

**3. During use**

- Never touch the machine when it is running and keep your hands away from any moving parts during machining
- Stay away from the machine when it is operational

**4. After machining**

- Use a brush or vacuum to clean chips from surfaces
- If linear guides, ball screws and racks are dusty, blow them with compressed air to keep them clean and unobstructed by chips
- Clean the floor and work area around the machine
- Clean and store personal protective equipment
- Mark any defective equipment and contact us if you encounter a problem

**5. Normal shutdown**

1. Complete current machining
2. Stop spindle
3. **Shut down Raspberry Pi** (proper shutdown)
4. Wait 30 seconds
5. Turn off control box

> **<i class="fas fa-info-circle" style="color: #2196f3;"></i> CAUTION** - Follow the order to avoid corruption of the Raspberry Pi SD card

**6. Emergency stop**

**In case of danger:**

1. **Immediately press** the red button
2. Cut power if necessary
3. Analyze the situation
4. Correct the problem
5. Reset (turn the button)
6. Redo a homing procedure

### 6.2 Workpiece clamping {#62-workpiece-clamping}

#### 6.2.1 Clamping systems supplied with base kit {#621-clamping-systems-supplied-with-base-kit}

**Wood screws:**

- For soft materials
- Direct screwing into spoilerboard
- Regular spacing

**Clamps with inserts:**

- For all materials
- M6 inserts in spoilerboard

#### 6.2.2 Clamping rules {#622-clamping-rules}

**<i class="fas fa-square-check" style="color: #4EBD7D;"></i> GOOD PRACTICES:**

- Minimum 4 clamping points
- Symmetrical distribution
- Check before machining

**<i class="fas fa-xmark" style="color: #d32f2f;"></i> PROHIBITIONS:**

- Manual clamping
- Adhesive alone
- Overhanging workpiece
- Excessive tightening (deformation)

> **<i class="fas fa-ban" style="color: #d32f2f;"></i> DANGER** - During machining, NEVER hold the workpiece by hand

### 6.3 Tool installation {#63-tool-installation}

#### 6.3.1 Tool change {#631-tool-change}

**Procedure:**

1. Wait for complete stop or machine pause
2. Move Z axis to high position
3. Unlock ER20 nut (supplied wrenches)
4. Remove tool (gloves strongly recommended)
5. Insert new tool
6. Tighten firmly (without excess)

#### 6.3.2 Tool length measurement {#632-tool-length-measurement}

**With the supplied tool probe:**

1. Place the probe on the workpiece or spoilerboard (depending on the Z0 coordinate defined in the program)
2. Position the spindle above the probe
3. Press the tool length measurement icon
4. Slow automatic descent
5. Contact and memorization of new Z0 position

### 6.4 Programming and machining {#64-programming-and-machining}

#### 6.4.1 Accepted formats {#641-accepted-formats}

- **G-code:** .nc, .ngc, .gcode
- **Generation:** Via any CAM software. Some examples:
  - Fusion 360 (recommended)
  - VCarve
  - FreeCAD
  - Others

#### 6.4.2 Operating modes {#642-operating-modes}

**Automatic mode:**

1. Load G-code file
2. Check simulation in PlanetCNC
3. Position workpiece origin (X0 Y0 Z0)
4. Start program (Start)

**Manual mode (JOG):**

- Movement by axes
- Variable speed (10-100%)
- Movement by increments possible (examples: 0.01, 0.1, 1, 10 mm)

**MDI mode:**

- Sending direct G-code commands
- Sequence testing
- Precise positioning

### 6.5 Monitoring during machining {#65-monitoring-during-machining}

#### 6.5.1 Check points {#651-check-points}

- Abnormal vibrations
- Unusual noise
- Chip quality
- Temperature near tool
- Workpiece clamping

#### 6.5.2 Anomalies and actions {#652-anomalies-and-actions}

| Anomaly              | Probable cause                             | Immediate action                 |
| :------------------- | :----------------------------------------- | :------------------------------- |
| **Vibrations**       | Worn tool or unsuitable cutting parameters | STOP → Check tool and parameters |
| **Smoke**            | Worn tool or unsuitable cutting parameters | EMERGENCY → Stop                 |
| **Loud noise**       | Very worn or broken tool                   | EMERGENCY → Stop                 |
| **Moving workpiece** | Insufficient clamping                      | EMERGENCY → Stop                 |

> In case of doubt → **IMMEDIATE STOP**

## 7. ADD-ONS AND OPTIONS {#7-add-ons-and-options}

### 7.1 Vacuum table {#71-vacuum-table}

#### 7.1.1 Specifications {#711-specifications}

- Plastic plenum with dedicated spoilerboard and integrated seals
- 5 independent zones
- Vacuum pump and connections
- Installation: 3 hours

#### 7.1.2 Use {#712-use}

**New clamping system for workpieces:**

1. Place workpiece on spoilerboard
2. Open necessary zones
3. Activate vacuum pump
4. Check hold (manual test)

Information about the kit and assembly guide can be found on our website:

<i class="fas fa-globe" style="color: #2196f3;"></i> [support.mekanika.io/products/vacuum-table/vacuum-table-fab](https://support.mekanika.io/products/vacuum-table/vacuum-table-fab)

We strongly recommend following our illustrated startup guide dedicated to the vacuum table.

### 7.2 Dust collection kit {#72-dust-collection-kit}

#### 7.2.1 Specifications {#721-specifications}

- Anti-static suction hose Ø100mm
- Compatible with most workshop vacuums
- Pivoting steel tube support
- Installation: 1 hour

Information about the kit and assembly guide can be found on our website:

<i class="fas fa-globe" style="color: #2196f3;"></i> [support.mekanika.io/products/dust-collection-kit](https://support.mekanika.io/products/dust-collection-kit)

### 7.3 Laser module (LSR) {#73-laser-module-lsr}

#### 7.3.1 Specifications {#731-specifications}

- Model: PLH3D-XT-50
- Power: 6W optical
- Wavelength: 445 nm (blue)
- Laser class: 4

> **<i class="fas fa-ban" style="color: #d32f2f;"></i> DANGER - CLASS 4 LASER**
>
> **Dedicated documentation:** See separate manual supplied with the machine

Information about the kit and assembly guide can be found on our website:

<i class="fas fa-globe" style="color: #2196f3;"></i> [support.mekanika.io/products/laser-head-6w](https://support.mekanika.io/products/laser-head-6w)

## 8. MAINTENANCE & TROUBLESHOOTING {#8-maintenance--troubleshooting}

We strongly recommend following our video maintenance guide, available on our website:

<i class="fas fa-globe" style="color: #2196f3;"></i> [support.mekanika.io/products/fab-cnc/maintenance](https://support.mekanika.io/products/fab-cnc/maintenance)

### 8.1 Preventive maintenance plan {#81-preventive-maintenance-plan}

| **FREQUENCY** | **OPERATION**                                  | **DURATION** | **MACHINE STOP** |
| :------------ | :--------------------------------------------- | :----------- | :--------------- |
| **Daily**     | Chip cleaning                                  | 10 min       | No               |
| **Daily**     | General visual inspection                      | 5 min        | No               |
| **Monthly**   | Lubrication of X/Y/Z guides                    | 15 min       | Yes              |
| **Monthly**   | Control box filter cleaning                    | 10 min       | Yes              |
| **Monthly**   | Y belt tension adjustment                      | 20 min       | Yes              |
| **Monthly**   | Greasing of ball screws and racks              | 15 min       | Yes              |
| **Monthly**   | Mechanical play check on linear systems        | 30 min       | Yes              |
| **Monthly**   | Complete fastener check                        | 45 min       | Yes              |
| **Annual**    | Complete machine overhaul                      | 4h           | Yes              |
| **Annual**    | Bearing replacement if necessary               | 2h           | Yes              |
| **Annual**    | Geometric calibration                          | 2h           | Yes              |

### 8.2 Lubrication {#82-lubrication}

A linear system must be sufficiently lubricated to function properly and avoid excessive wear or overheating. The required lubrication interval is determined by environmental conditions.

Generally, lubrication is necessary every 100 to 200 hours of operation. We recommend using lithium-based greases, which perform well in high-load applications and have good oxidation stability.

**Procedure:**

1. Clean before greasing (cloth and isopropyl alcohol)
2. Apply grease moderately
3. Perform 10 complete machine travel cycles
4. Wipe off excess grease

### 8.3 Spare parts {#83-spare-parts}

All parts of the machine and control box can be purchased individually as spare parts.

Please contact us directly about this.

When ordering spare parts, please provide information about the machine model, size and part number available according to the construction instructions.

## 9. TROUBLESHOOTING {#9-troubleshooting}

### 9.1 Troubleshooting and diagnostics {#91-troubleshooting-and-diagnostics}

If you have a problem with your machine, please consult our troubleshooting guides available online:

<i class="fas fa-globe" style="color: #2196f3;"></i> [support.mekanika.io/products/fab-cnc/troubleshoot](https://support.mekanika.io/products/fab-cnc/troubleshoot)

### 9.2 Technical support {#92-technical-support}

#### 9.2.1 Before contacting support {#921-before-contacting-support}

**Information to prepare:**

- Machine model (FAB)
- Machine serial number (located under the control box)
- Order number
- Problem description
- Photos/videos if possible

#### **CONTACT FORM**

<i class="fas fa-globe" style="color: #2196f3;"></i> [www.mekanika.io/en/contact-support](https://www.mekanika.io/en/contact-support)

## 10. TRANSPORTATION & STORAGE {#10-transportation--storage}

### 10.1 Machine Transportation {#101-machine-transportation}

If you wish to transport the machine, pay special attention to its dimensions and weight, you may need additional people for transport.

Never lift heavy loads above people.

Avoid loading the machine frame unilaterally during transport.

### 10.2 Packaging & Waste {#102-packaging--waste}

If you do not wish to reuse the device packaging, please sort it according to local sorting rules and take it to a waste collection center for recycling.

If you need to replace certain machine components, or decommission it, please go to your local waste disposal center and perform selective sorting.

| **Material**     | **Components**                      | **Stream**       |
| :--------------- | :---------------------------------- | :--------------- |
| **Aluminum**     | Profile structure                   | Metal recycling  |
| **Steel**        | Connection plates, shafts, fasteners | Metal recycling  |
| **Electronics**  | Control boards, motors              | WEEE\*           |
| **Cables**       | Sheathed copper                     | WEEE\*           |
| **Plastics**     | Cable chains, connection plates     | Plastic sorting  |

\* _Waste Electrical and Electronic Equipment_

### 10.3 Storage {#103-storage}

If the machine or its components are not used for an extended period, please observe the following points regarding storage:

- Store the machine and its components only in closed rooms
- Protect the machine and its components from moisture, cold, heat and direct solar radiation
- Store the machine and its components away from dust and cover if necessary
- The storage location must not be subject to vibrations.

---

**END OF INSTRUCTION MANUAL**

This manual is the property of MEKANIKA SRL. Any reproduction, even partial, is prohibited without written authorization.
<br/>

**IMPORTANT NOTES:**

- This manual must remain with the machine
- In case of resale, transmit all documents
- Updates available at [support.mekanika.io/download-center/cnc-milling](https://www.mekanika.io/en/contact-support)
- For any questions: info@mekanika.io
  <br/>

**Keep this manual for future reference**

---

**© 2025 MEKANIKA SRL - All rights reserved**
