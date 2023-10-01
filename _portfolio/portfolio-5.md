---
title: "Portfolio Project Number 5"
excerpt: "Project Title:<br>Investigating the Structure, Properties, and Behavior Prediction of GaAs Semiconductor Lasers with 808 nm Radiation Wavelength and Bandwidth Less than 5 nm<br/><img src='/images/name.png'>"
collection: portfolio
---



* May 2018 - Sep. 2018: Undergraduate Project
  * [Iran University of Science and Technology](http://www.iust.ac.ir/en)
  * Supervisor: [Prof. Yazdanpanah](https://www.linkedin.com/in/vahid-yazdanpanah-83a57231/)
  * Title: Investigating the Structure, Properties, and Behavior Prediction of GaAs Semiconductor Lasers with 808 nm Radiation Wavelength and Bandwidth Less than 5 nm
  * Duties included: Investigating and analyzing the structure of **Quantum Well Lasers**; Modeling 808 nm Laser **Structures** using **Wolfram Mathematica** Software and **Silvaco** Software; **Optimizing** the **bandwidth** of **semiconductor laser** output spectrum; Examining the influence of various laser **characteristics**, including the **active region** width, **waveguide layer** width, and **threshold current density**, on laser bandwidth.


<h1>Abstract</h1>
<div style='text-align: justify;'>
In the simulation conducted for this thesis, the effect of various laser parameters on its output spectrum is examined. Through these investigations, it was determined that the laser bandwidth is directly influenced by three parameters: t (the width of the active area), d (the total width of the active area and waveguide layers), and Jth (the threshold current density). However, no effect on the laser output spectrum was observed from other parameters, such as γ (cavity loss), L (cavity length), A (cavity cross-sectional area), etc.
 <br>
To assess the impact of these three mentioned parameters, two of them are designated as variables in each trial, while the remaining parameter is maintained as a constant. Subsequently, utilizing Wolfram Mathematica software, the bandwidth diagram will be generated with respect to the two variable parameters. The effect of these parameters on the laser bandwidth will be observed and assessed. The range of variable values is selected to ensure that the laser's output bandwidth remains below 5 nm, aligning with the project's objectives.
  <br>
  <br>
</div>


<html>
<head>
<style>
  table {
    border-collapse: collapse;
    width: 100%;
  }
  table, td {
    border: none;
  }
  td {
    vertical-align: middle;
    text-align: center;
  }
  img {
    max-width: 100%;
    height: auto;
  }
</style>
</head>
<body>
<h1>1. The First Laser Structure</h1>
 <div style='text-align: justify;'>
 The laser structure proposed here comprises three GaAs quantum wells that are separated by Al0.35Ga0.65As barriers. The presence of more than one quantum well in the structure leads to an elevation in the probability of radiative recombination, driven by the heightened quantum confinement of electrons and holes and the augmented density of states. Furthermore, increased radiative recombination guarantees an enhancement in output efficiency.
 <br>
 <br>
 </div>
    <!-- Image container with caption -->
    <div class="image-container">
        <img src='/images/project5_16.PNG' alt="Image Alt Text">
        <figcaption><span class="fig-caption">Fig.1</span>: The first configuration of the semiconductor laser.</figcaption>
    </div>


<table>
  <tr>
    <td><img src='/images/project5_17.png' alt="Image 1"></td>
    <td><img src='/images/project5_18.png' alt="Image 2"></td>
    <td><img src='/images/project5_19.png' alt="Image 3"></td>
  </tr>
  <tr>
    <td><strong>Fig.1_1</strong>: In this case, it is assumed that the parameters 'd' and 't' are variable, while the 'J<sub>th</sub>' parameter is held constant. The bandwidth diagram is created using the Plot-3D command in Wolfram Mathematica. As indicated by the plot, Δλ is found to be independent of 't,' but it is influenced by changes in 'd'. It is noteworthy that the slope of Δλ experiences an increasing shift for 'd' values smaller than 60 nm.</td>
    <td><strong>Fig.1_2</strong>: With the assumption that the two parameters, 'd' and 'J<sub>th</sub>', are variable, while the parameter 't' remains constant, the bandwidth diagram is generated using the Plot-3D command in Wolfram Mathematica. As illustrated in the plot, Δλ is observed to be responsive to variations in both 'd' and 'J<sub>th</sub>' in this particular scenario. These changes peak when 'J<sub>th</sub>' values exceed 1x10<sup>6</sup> amperes per square and 'd' values are below 40 nm.</td>
    <td><strong>Fig.1_3</strong>: With the assumption that the two parameters, 't' and 'J<sub>th</sub>', are variable, while the parameter 'd' is held constant, the bandwidth diagram is generated using the Plot-3D command in Wolfram Mathematica. As portrayed in the plot, in this scenario, Δλ is found to be unaffected by 't' but exhibits a linear response to alterations in 'J<sub>th</sub>'.</td>
  </tr>
</table>

</body>
</html>

<br>

<body>
<h1>2. The Second Laser Structure</h1>
  <div style='text-align: justify;'>
According to band edge calculations, the band gap energy corresponding to the InxAlyGa1-x-yAs structure with In and Al contents of 0.12 and 0.15, respectively, is found to be 1.48 eV at room temperature. Since the limitation of the quantum well is causing the energy levels of the ground state to be shifted towards higher energies, the radiant energy of the structure is determined by the length of the quantum well. According to the laboratory results reported for this structure, light is emitted at 792 nm at zero Kelvin temperature and at 808±1 nm at room temperature when a quantum well with a thickness of 8 nm is employed.
 <br>
 <br>
 </div>
    <!-- Image container with caption -->
    <div class="image-container">
        <img src='/images/project5_20.PNG' alt="Image Alt Text">
        <figcaption><span class="fig-caption">Fig.2</span>: The second configuration of the semiconductor laser.</figcaption>
    </div>


<table>
  <tr>
    <td><img src='/images/project5_21.png' alt="Image 1"></td>
    <td><img src='/images/project5_22.png' alt="Image 2"></td>
    <td><img src='/images/project5_23.png' alt="Image 3"></td>
  </tr>
  <tr>
    <td><strong>Fig.2_1</strong>: In this case, it is assumed that the two parameters, 'd' and 't', are variable, while the 'J<sub>th</sub>' parameter is held constant. The bandwidth diagram is generated using the Plot-3D command in Wolfram Mathematica. As illustrated in the plot, Δλ is found to be unaffected by 't' and remains consistent regardless of its variation. However, it is observed to be sensitive to changes in 'd'. Notably, the slope of Δλ experiences an increasingly pronounced shift for 'd' values below 40 nm.</td>
    <td><strong>Fig.2_2</strong>: With the assumption that the two parameters, 'd' and 'J<sub>th</sub>,' are variable while keeping the parameter 't' constant, the bandwidth diagram is constructed using the Plot-3D command in Wolfram Mathematica. As observed in the plot, Δλ exhibits sensitivity to variations in both 'd' and 'Jth.' These sensitivities reach their peak when 'Jth' values exceed 1x10<sup>6</sup> ampere/m², and 'd' values are less than 40 nm.</td>
    <td><strong>Fig.2_3</strong>: With the assumption that the two parameters, 't' and 'J<sub>th</sub>,' are variable while keeping the parameter 'd' constant, the bandwidth diagram is generated using the Plot-3D command in Wolfram Mathematica. As observed in the plot, Δλ remains unaffected by 't' but exhibits linear changes in response to variations in 'J<sub>th</sub>'.</td>
  </tr>
</table>

</body>

<br>

<body>
<h1>3. The Third Laser Structure</h1>
    <!-- Image container with caption -->
    <div class="image-container">
        <img src='/images/project5_24.PNG' alt="Image Alt Text">
        <figcaption><span class="fig-caption">Fig.3</span>: The third configuration of the semiconductor laser.</figcaption>
    </div>


<table>
  <tr>
    <td><img src='/images/project5_25.png' alt="Image 1"></td>
    <td><img src='/images/project5_26.png' alt="Image 2"></td>
    <td><img src='/images/project5_27.png' alt="Image 3"></td>
  </tr>
  <tr>
    <td><strong>Fig.3_1</strong>: With the assumption that the two parameters, 'd' and 't,' are variable and the 'J<sub>th</sub>' parameter is held constant, the bandwidth diagram is generated using the Plot-3D command in Wolfram Mathematica. As depicted in the image, Δλ is found to be unaffected by 't' but is sensitive to changes in 'd.' Notably, the slope of Δλ undergoes greater variation when 'd' values are less than 3x10<sup>-8</sup>.</td>
    <td><strong>Fig.3_2</strong>: By assuming that the two parameters, 'd' and 'J<sub>th</sub>,' are variable, while maintaining the parameter 't' as constant, the bandwidth diagram is generated using the Plot-3D command in Wolfram Mathematica. As observed in the plot, Δλ is found to be sensitive to variations in both 'd' and 'Jth.' These sensitivities reach their peak when 'J<sub>th</sub>' values exceed 1.5 x 10^6 ampere/m^2, and 'd' values are below 35 nm.</td>
    <td><strong>Fig.3_3</strong>: With the assumption that the two parameters, 't' and 'Jth,' are variable, while the parameter 'd' is held constant, the bandwidth diagram is created using the Plot-3D command in Wolfram Mathematica. As depicted in the diagram, Δλ remains unaffected by 't' but undergoes linear changes in response to alterations in 'J<sub>th</sub>'.</td>
  </tr>
</table>

</body>
</head>
</html>
