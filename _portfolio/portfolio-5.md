---
title: "Portfolio Project Number 4"
excerpt: "Project Title:<br>Investigating the Structure, Properties, and Behavior Prediction of GaAs Semiconductor Lasers with 808 nm Radiation Wavelength and Bandwidth Less than 5 nm<br/><br><img src='/images/first_photo.png' style='max-width: 320px; max-height: 240px;' alt='Your Image'>"
collection: portfolio
---



* May 2018 - Sep. 2018: Undergraduate Project
  * [Iran University of Science and Technology](http://www.iust.ac.ir/en)
  * Supervisor: [Prof. Yazdanpanah](https://www.linkedin.com/in/vahid-yazdanpanah-83a57231/)
  * Title: Investigating the Structure, Properties, and Behavior Prediction of GaAs Semiconductor Lasers with 808 nm Radiation Wavelength and Bandwidth Less than 5 nm
  * Duties included: Investigating and analyzing the structure of **Quantum Well Lasers**; Modeling 808 nm Laser **Structures** using **Wolfram Mathematica** Software and **Silvaco** Software; **Optimizing** the **bandwidth** of **semiconductor laser** output spectrum; Examining the influence of various laser **characteristics**, including the **active region** width, **waveguide layer** width, and **threshold current density**, on laser bandwidth.


<br>
<h1>Abstract</h1>
<div style='text-align: justify;'>
In this project, the examination of the output spectrum of the laser under various laser parameters is performed via simulation using Wolfram Mathematica software. It was found that the laser bandwidth is directly affected by three parameters: t (the width of the active area), d (the total width of the active area and waveguide layers), and Jth (the threshold current density). In each trial, two of these parameters were designated as variables, while the remaining parameter was kept constant. Subsequently, the bandwidth diagram was generated with respect to the two variable parameters. The impact of these parameters on the laser bandwidth was observed and assessed.
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
 The laser structure proposed here comprises three GaAs quantum wells that are separated by Al<sub>0.35</sub>Ga<sub>0.65</sub>As barriers. The presence of more than one quantum well in the structure leads to an elevation in the probability of radiative recombination, driven by the heightened quantum confinement of electrons and holes and the augmented density of states. Furthermore, increased radiative recombination guarantees an enhancement in output efficiency [1].
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
    <td><strong>Fig.1_2</strong>: With the assumption that the two parameters, 'd' and 'J<sub>th</sub>', are variable, while the parameter 't' remains constant, the bandwidth diagram is generated using the Plot-3D command in Wolfram Mathematica. As illustrated in the plot, Δλ is observed to be responsive to variations in both 'd' and 'J<sub>th</sub>' in this particular scenario. These changes peak when 'J<sub>th</sub>' values exceed 1x10<sup>6</sup> A/m<sup>2</sup> and 'd' values are below 40 nm.</td>
    <td><strong>Fig.1_3</strong>: With the assumption that the two parameters, 't' and 'J<sub>th</sub>', are variable, while the parameter 'd' is held constant, the bandwidth diagram is generated using the Plot-3D command in Wolfram Mathematica. As portrayed in the plot, in this scenario, Δλ is found to be unaffected by 't' but exhibits a linear response to alterations in 'J<sub>th</sub>'.</td>
  </tr>
</table>

</body>
</html>

<br>

<body>
<h1>2. The Second Laser Structure</h1>
  <div style='text-align: justify;'>
According to band edge calculations, the band gap energy corresponding to the In<sub>x</sub>Al<sub>y</sub>Ga<sub>1-x-y</sub>As structure with In and Al contents of 0.12 and 0.15, respectively, is found to be 1.48 eV at room temperature. Since the limitation of the quantum well is causing the energy levels of the ground state to be shifted towards higher energies, the radiant energy of the structure is determined by the length of the quantum well. According to the laboratory results reported for this structure, light is emitted at 792 nm at zero Kelvin temperature and at 808±1 nm at room temperature when a quantum well with a thickness of 8 nm is employed [1].
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
    <td><strong>Fig.2_2</strong>: With the assumption that the two parameters, 'd' and 'J<sub>th</sub>,' are variable while keeping the parameter 't' constant, the bandwidth diagram is constructed using the Plot-3D command in Wolfram Mathematica. As observed in the plot, Δλ exhibits sensitivity to variations in both 'd' and 'Jth.' These sensitivities reach their peak when 'Jth' values exceed 1x10<sup>6</sup> A/m², and 'd' values are less than 40 nm.</td>
    <td><strong>Fig.2_3</strong>: With the assumption that the two parameters, 't' and 'J<sub>th</sub>,' are variable while keeping the parameter 'd' constant, the bandwidth diagram is generated using the Plot-3D command in Wolfram Mathematica. As observed in the plot, Δλ remains unaffected by 't' but exhibits linear changes in response to variations in 'J<sub>th</sub>'.</td>
  </tr>
</table>

</body>

<br>

<body>
<h1>3. The Third Laser Structure</h1>
   <div style='text-align: justify;'>
   It was observed that light is emitted at a wavelength of 805 nm at room temperature by the two structures that were previously investigated for this system. Due to the considerably larger active layer thickness of 40 nm in the previous structures compared to the typical thickness (t < 15 nm) used for quantum wells, it was found that the impact of thickness on the wavelength of the output light in this system is not substantial, and the edge of the conduction band and the capacitance are regarded as the ground state energy of the electron and the hole, respectively.
<br>
In this manner, achieving an output wavelength of 808 nm at room temperature can only be accomplished by altering the content of participating elements in the active region. The calculations conducted on the band structure reveal that the structure in which the active region In<sub>x</sub>Ga<sub>1-x</sub>As<sub>y</sub>P<sub>1-y</sub> has an In content equal to 0.16 (with Ga content of 0.84) and an As content equal to 0.71 (with P content of 0.29) emits light at a wavelength of approximately 808 nm at room temperature. In such a case, the inconsistency of the In<sub>0.16</sub>Ga<sub>0.84</sub>As<sub>0.71</sub>P<sub>0.29</sub> network with the GaAs network is only 0.09%. This slight inconsistency ensures the possibility of two-dimensional growth with significant thicknesses of In<sub>0.16</sub>Ga<sub>0.84</sub>As<sub>0.71</sub>P<sub>0.29</sub>. Additionally, In<sub>0.16</sub>Ga<sub>0.84</sub>As<sub>0.71</sub>P<sub>0.29</sub> possesses a direct energy gap, indicating a high probability of electron-hole recombination within this system [1].
 <br>
 <br>
 </div>
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
    <td><strong>Fig.3_2</strong>: By assuming that the two parameters, 'd' and 'J<sub>th</sub>,' are variable, while maintaining the parameter 't' as constant, the bandwidth diagram is generated using the Plot-3D command in Wolfram Mathematica. As observed in the plot, Δλ is found to be sensitive to variations in both 'd' and 'Jth.' These sensitivities reach their peak when 'J<sub>th</sub>' values exceed 1.5 x 10<sup>6</sup> A/m<sup>2</sup>, and 'd' values are below 35 nm.</td>
    <td><strong>Fig.3_3</strong>: With the assumption that the two parameters, 't' and 'Jth,' are variable, while the parameter 'd' is held constant, the bandwidth diagram is created using the Plot-3D command in Wolfram Mathematica. As depicted in the diagram, Δλ remains unaffected by 't' but undergoes linear changes in response to alterations in 'J<sub>th</sub>'.</td>
  </tr>
</table>

</body>









<html>
<head>
    <style>
     

        /* Style for the left column */
        .column-left {
            float: left;
            width: 50%;
        }

        /* Style for the right column */
        .column-right {
            float: left;
            width: 50%;
        }

        /* Style for the image container */
        .image-container {
            max-width: 400px; /* Set the maximum width for your images */
            margin-bottom: 20px; /* Add spacing between images and captions */
            font-size: 20px; /* Adjust the value to your preferred font size */
        }

        /* Style for images */
        .image-container img {
            width: 100%; /* Make the image width match the container width */
            height: auto; /* Maintain aspect ratio */
        }

        /* Style for captions */
        .image-container figcaption {
            text-align: center; /* Center-align the caption */
        }

        
        /* Style for the "Fig." label */
        .fig-caption {
           font-weight: bold; /* Make the "Fig." text bold */
            font-size: 20px; /* Set the desired font size (adjust the value as needed) */
        }

    </style>
</head>
</html>

<br>
<br>
<p>
  <h2>Reference:</h2>
  <cite>[1] Semiconductor Optoelectronic Devices</cite><br>
  Author(s): Bhattacharya, Pallab<br>
  Publisher: Prentice-Hall, Inc.<br>
  Publication Year: 1997
</p>
