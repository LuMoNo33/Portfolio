---
title: "Custom Vacuum Chamber for Nanomaterial Characterization"
date: 2025-03-15T15:34:30-04:00
categories:
  - Engineering Project
tags:
  - Material Characterization
  - Design & Manufacture
  - Nanomaterials

share: false
---

During the course *Experimental Characterization of Materials*, we developed a strong foundation in synthesis and characterization methods for advanced materials. The main challenge was to create and analyze a carbon fiber plate doped with carbon nanostructures, with the objective of improving supercapacitor performance by increasing surface area compared to a flat plate.

A brief summary of this five-week project can be found on this page:



<div style="position: relative; width: 100%; height: 0; padding-top: 56.2500%;
 padding-bottom: 0; box-shadow: 0 2px 8px 0 rgba(63,69,81,0.16); margin-top: 1.6em; margin-bottom: 0.9em; overflow: hidden;
 border-radius: 8px; will-change: transform;">
  <iframe loading="lazy" style="position: absolute; width: 100%; height: 100%; top: 0; left: 0; border: none; padding: 0;margin: 0;"
    src="https://www.canva.com/design/DAGxlLrtFNM/1EgOq7BAqh39YYCcfc_HWQ/view?embed" allowfullscreen="allowfullscreen" allow="fullscreen">
  </iframe>
</div>
<a href="https:&#x2F;&#x2F;www.canva.com&#x2F;design&#x2F;DAGcG1RXJMI&#x2F;I-Zn5XAyMOniuBLSjnQv_g&#x2F;view?utm_content=DAGcG1RXJMI&amp;utm_campaign=designshare&amp;utm_medium=embeds&amp;utm_source=link" target="_blank" rel="noopener">Characterization of nanostructures and vacuum design summary </a> by Luis Eduardo Montoya Nogami


We gained hands-on experience by preparing a solution of Polyacrylonitrile (PAN), Dimethylformamide (DMF), and Fe nanoparticles acting as seeds. This solution was transformed into nanofibers through the **electrospinning** method.  

<img src="{{ site.baseurl }}/assets/images/ElectrospinningSetup.png" alt="ElectroSpinning" width="600" />
*Electrospinning diagram and experimental arrangement*

A section of the nanofiber mat was then placed in a CVD furnace for pyrolysis and carbon deposition. This process produced carbon nanofibers, with the aim of obtaining carbon nanotubes growing around the iron nanoparticles. 


<img src="{{ site.baseurl }}/assets/images/CVDSetup.png" alt="CVD Setup" width="600" />
*CVD furnace*

Although carbon nanotubes were not achieved, we successfully observed carbon nanostructures, which can still enhance surface area and improve capacitor performance. 


<table>
  <tr>
    <td><img src="{{ site.baseurl }}/assets/images/SEMFibersNS.png" alt="Imagen 3" width="450" /></td>
    <td><img src="{{ site.baseurl }}/assets/images/SEMNSClose.png" alt="Imagen 1" width="450" /></td>
  </tr>
</table>
*SEM images of fibers and nanostructures*


To accurately characterize electrical conductivity — while isolating effects from contaminants, temperature, and possibly light — we designed a custom **vacuum chamber** with the following requirements:

- Maximum volume: 4 L  
- Pressure: 3 × 10^-3 Torr  
- Operating temperature range: -150 °C to 150 °C  
- Ability to irradiate samples with visible light of different wavelengths  
- Designed to be cost-effective  
- Versatile for multiple applications  



The chamber was designed in **Fusion360** for its flexibility and ease of use. Its main body was based on standard water-supply pipe sizes in Stainless Steel 304, chosen to reduce outgassing and minimize costs.

<table>
  <tr>
    <td><img src="{{ site.baseurl }}/assets/images/VacuumLidClean.jpg" alt="Imagen 3" width="450" /></td>
    <td><img src="{{ site.baseurl }}/assets/images/MainBody3.jpg" alt="Imagen 1" width="450" /></td>
  </tr>
</table>
*Vacuum chamber assembled and main body component*

To achieve higher vacuum levels, gasket selection was crucial: frequently accessed ports use Viton O-rings, while permanent seals rely on copper gaskets for superior tightness. 



<table>
  <tr>
    <td><img src="{{ site.baseurl }}/assets/images/VTopLid.png" alt="Imagen 1" width="460" /></td>
    <td><img src="{{ site.baseurl }}/assets/images/VBottomLid.png" alt="Imagen 3" width="450" /></td>
  </tr>
</table>
*Top lid with O-ring gasket and bottom lid with CF copper gasket*


For optical access, **Thorlabs fused silica viewports** were installed. These allow samples to be illuminated with light sources across the visible spectrum. 


<table>
  <tr>
    <td><img src="{{ site.baseurl }}/assets/images/ThorlabsViewport.png" alt="Imagen 1" width="460" /></td>
    <td><img src="{{ site.baseurl }}/assets/images/ThorlabsViewportExploded.png" alt="Imagen 3" width="450" /></td>
  </tr>
</table>
*Thorlabs UV fused-silica viewport (185 nm – 2.1 μm) and exploded view*

The most important component inside the system is the **sample holder**, which secures the four probes for electrical transport measurements, thermocouples, structural support, and electrical insulation. Due to its resemblance to the arc reactor, it was named the **“Arc Component.”**

<img src="{{ site.baseurl }}/assets/images/ARCDrawingv4.jpeg" alt="Arc Component" width="600" />
*Arc Component drawing*

To reach -150 °C, liquid nitrogen was circulated through a coil surrounding the holder. Since experiments are performed in vacuum, only conductive and radiative heat transfer were considered. 


<img src="{{ site.baseurl }}/assets/images/ElectrospinningSetup.png" alt="LN2 line" width="600" />
*Liquid nitrogen stainless steel line for sample cooling*



In addition, a resistive heating cartridge was installed at the back of the sample holder.  

Finite Element Analysis (FEA) and heat transfer simulations were carried out to verify the reliability of the Arc Component, both structurally and thermally.  

<table>
  <tr>
    <td><img src="{{ site.baseurl }}/assets/images/FEMArc.png" alt="Imagen 3" width="450" /></td>
    <td><img src="{{ site.baseurl }}/assets/images/HeatTransfer.png" alt="Imagen 1" width="460" /></td>
  </tr>
</table>
*Finite Element Analysis under 10 kg load and cooling system heat transfer simulation*



The simulations confirmed that the temperature requirements were achieved, and that the Arc Component would not undergo plastic deformation unless subjected to loads greater than 10 kg — well above expected operating conditions.  



The full report on the project, vacuum system design, and characterization methods can be found here:

<iframe src="https://drive.google.com/file/d/1ftvaXmRrAS26axOhQdAPuxhg4YpG7Px3/preview" width="640" height="480" allow="autoplay"></iframe>
