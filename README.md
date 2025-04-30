# AirGo Design Atlas-AI

![img_AtlasAI](assets/images/AtlasAI_logo_256x256.png)

AirGo Design's ATLAS-AI, a proprietary AI-assisted CAE simulation software, offers a suite of tools for manipulating FEM models with components made of highly anisotropic Fiber-Reinforced Thermoplastic Composites (FRTC).

The growing demand for sustainable and high-performance engineering polymers has led to the development of injection molded (Short/Long) Fiber Reinforced Thermoplastics (FRT). This class of reinforced polymers have been utilized in the industry for decades, their full potential has been hindered by conventional CAE simulation methods' inability to accurately simulate their material behavior on components level. This limitation has confined their application primarily to less demanding secondary structures. FRT represents a vital segment within the development of environmentally sustainable engineering plastics, poised to supplant metals in heavy-duty components, applied in aerospace, automotive, electronics etc.

---

## The Challenge with Designing FRT Heavy-duty Components

The mechanical performance of Fiber Reinforced Thermoplastics components are intricately tied to geometry, material selection, and manufacturing parameters. Unlike its metallic counterparts, Fiber Reinforced Thermoplastics components exhibit strong anisotropy—whereby stiffness and strength are influenced by fiber orientation. Fiber orientation is heavily dependent on a multitude of geometry and manufacturing factors.

![img_FOT_in_FRT](assets/images/FOT_in_FRT_component.png)

When it comes to simulation, working between micro-scale and macro-scale demands significant time, expertise in various domains, and computing resources. Furthermore, accessing material property data (including material data for the components of the compound, filler etc.) and allowables are not always straightforward, often necessitating costly laboratory testing and specialized knowledge. ATLAS-AI addresses these issues head-on.

---

## Why use ATLAS-AI?

### AI and Data-Driven
Utilizing a statistically derived material property database, micro-level simulation becomes unnecessary. Fiber orientation data is meticulously adjusted based on structure geometry for accuracy.

### Fast Yet Accurate
ATLAS-AI delivers fast results without sacrificing accuracy. It captures multi-layer property variations through the thickness of the part—without requiring high-resolution FEM models. Since it operates entirely in pre- and post-processing, there’s no need for co-simulation or data exchange with external software. This results in:
 - 95% faster load times
 - 90% smaller result files
 - 65% lower RAM usage

### Proprietary Failure Model 
ATLAS-AI incorporates a custom-developed failure criterion that outperforms conventional models by leveraging AI-generated allowables, enabling more accurate and reliable failure prediction.

### Material/Software Agnostic 
ATLAS-AI is fully compatible with a broad range of FEA platforms—supporting both implicit and explicit solvers—and is applicable to all types of fiber-reinforced thermoplastics (FRTs), regardless of chemical composition.

### Third-Party Validated
Blind validation exercises were conducted with Mitsubishi Chemicals Advanced Materials (MCAM) and SAFRAN on two different FRTC material projects, i.e., comparing Atlas-AI vs conventional CAE methods. Atlas-AI models completed with less time and predictions were closer to actual physical testing data, in comparison to conventional CAE simulation undertaken by MCAM and Safran engineering teams.

---

##  Where does Atlas-AI Fit in?

AirGo Design’s ATLAS-AI suits streamline structural analysis by bridging the gap between injection molding simulations and accurate FEA models.

![img_wheredowefit](assets/images/AtlasAI_overview.png)

Unlike conventional tools that merely map fiber orientation tensor data to a separate structural mesh, ATLAS-AI intelligently adapts anisotropic material properties based on both geometry and material selection.

---

## ATLAS-AI at a Glance

ATLAS-AI currently consists of 5 main modules:-AtlasMat, AtlasPre, AtlasPost, AtlasXL, and AtlasEndura.

![The full suite](assets/images/AtlasAI_alltools.png)


## Workflow

Shown below is an example of how the modules are typically integrated into a FEM analysis. AtlasPre takes the information from the manufacturing simulation and integrates the anisotropic properties to the FEM model. After the simulation, AtlasPost is used to post-process and generate result images.

![Workflow](assets/images/General_workflow01.png)

---
  
## About us
AirGo develops innovative lightweight technologies for demanding applications in various industries. https://www.airgodesign.com/company

### The EV Industry

The demand for battery power, measured in gigawatt-hours, is expected to grow from 185 GWh in 2020 to 2,035 GWh by 2030, representing an 11-fold increase, with nearly 90% of the demand from transportation alone. Lithium-ion is the most dominant rechargeable battery technology, accounting for just over 40% of the global revenue share in 2022, driven mostly by its use in the EV industry.

Over the years, metals have dominated the market for EV battery cases owing to their advantages, such as being extremely robust and impact-resistant, high-temperature tolerance, flame-retardant, and affordable. However, in recent years, the penetration of composite battery cases has been growing at a rapid pace owing to factors such as lighter weight, high production rate, and to a certain extent, higher mechanical performance compared to metals. 

AirGo is looking into composite battery enclosures for the rapidly emerging short/medium-haul electric aircraft market, i.e., a combination of commercial urban air mobility vehicles (UAVs, eVTOLs, etc.) (e.g., E-hang EH216-S, Xpeng AeroHT, etc.) and larger regional/private jets e-aircraft such as COMAC ARJ21, Heart airspace’s ES-30, Energia Electric (E9-FE), etc. This market was valued at $9 billion in 2022, with a 20% CAGR, and has the prospect to reach $67 billion by 2033.

Atlas-AI provide the necessary tools for the job.

---


## Contact Us

For more information or a demo, email to atlas@airgodesign.com