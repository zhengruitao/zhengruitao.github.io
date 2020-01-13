---
<!-- layout: archive -->
title: Research Experiences
excerpt: "Zhengrui tao Research"
permalink: /research/
author_profile: true
---
Research Experience
======

* ***<font color="#660000">Virtual Machining System: Chatter Stability Analysis and Feed Rate Optimization</font>***
  * *Research Assistant, Supervised by Prof. Ming Chen*                                                              
  * *Shanghai, China; 09/2019 - Present*
  * <p align="center"><img src="https://zhengruitao.github.io/images/thesis_framework.jpg?raw=true" alt="Photo" style="width: 800px;"/></p>
  * Established a Virtual Machining System specific to thin-wall workpieces, including chatter stability analysis and feed rate
optimization, contributing to a **43**% reduction in average cycle time and **7.4**-fold improved surface finish for automotive
engine turbine machining
  * Established milling dynamics model considering regenerative chatter, and got [Stability Lobe Diagram](http://zhengruitao.github.io/images/SLD.jpg) using the zero-order frequency domain solution of which the relative transfer function includes the modal parameters of tool and workpiece
  * Obtained the cutter-workpiece engagement area by geometric simulation, utilized the Boolean operation to extract geometrical
parameters according to the minimum octants contacting with the cutter, and optimized the feed rate in NC code with Genetic
Algorithms to maximize the Material Removal Rate
  * [More details about Master's thesis](http://zhengruitao.github.io/files/Optimization_Slide.pdf)
  
* ***<font color="#660000">Tool Condition Monitoring: Diagnostics, Prognostics, and Remaining Useful Life Prediction</font>***
  * *Research Assistant, Supervised by Prof. Ming Chen & Prof. Mohamed EL Mansori*　　　　　　　           
  * *Shanghai, China; 09/2018 - 09/2019*
  * <p align="center"><img src="https://zhengruitao.github.io/images/LSTM-HMM-scheme.jpg?raw=true" alt="Photo" style="width: 800px;"/></p>
  * Developed a hybrid framework based on [LSTM](http://zhengruitao.github.io/images/LSTM.jpg) and [HMM](http://zhengruitao.github.io/images/GMM-HMM.jpg) capable of performing TCM during high-speed milling Ti-6Al-4V 
with diagnostic accuracy reaching up to **0.96** and prognostics MSE decreasing by **93.9**%
  * Employed the global model (stacked LSTM network) to identify the current tool wear stage, inferred the wear accumulation
state sequence using the best-fitted HMM, then calculated the mean wear amount and the associated confidence interval based
on the state sequence and wear statistics
  * <p align="center"><img src="https://zhengruitao.github.io/images/CNN-BLSTMs-structure.jpg?raw=true" alt="Photo" style="width: 800px;"/></p>
  * Proposed another integrated model combining [CNN](http://zhengruitao.github.io/images/CNN_structure.jpg) with stacked bidirectional and unidirectional LSTMs [(SBULSTM)](http://zhengruitao.github.io/images/Stacked-Bidirectional-and-Unidirectional-LSTM-Networks.jpg) to
predict remaining useful life during machining 6063 aluminum alloy smartphone backplate with the three metrics (RMSE/
accuracy/ score) decreased by **77**%, increased by **25**% and improved by **38**% compared with the Random Forest model
  * Utilized CNN for local feature extraction and dimension reduction, introduced the SBULSTM network to denoise and encode
the temporal information, built multiple fully connected layers on the top of the CNN-SBULSTM network to add nonlinearity, and employed one regression layer to generate the target RUL
  * Journal Papers: [J1]/[J5]/[J7]; Conference paper: [C2]
    
* ***<font color="#660000">Research on Helical Milling Specialized Tool for CFRP/Titanium alloy</font>***
  * *Research Assistant, Supervised by Prof. Jinyang Xu*　　　　　　　　　　　　　　　　　　                       
  * *Shanghai, China; 09/2017 - 07/2018*
  * Designed a specialized helical milling tool with distributed multi-point front cutting edge, and evaluated the cutting performances with machined titanium alloy holes burr-free, CFRP holes without delimitation and the service life improved by **50**%
and 35% compared to the traditional end mill
  * Analyzed the chip-splitting results by simulating the undeformed chip formation and each cutting edge’s trajectory, and
proceed to iteratively update the structure and geometric parameters of the specialized tool based on the simulation results
  * Journal Papers:[J4]; Conference paper: [C1]
  
* ***<font color="#660000">Structural Design and Sealing Performance Analysis of Biomimetic Flexible Sealing Ring</font>***　　       
  * *Research Assistant, Supervised by Prof. Jinyang Xu*　　　　　　　　　　　　　　　　　　                        
  * *Shanghai, China; 09/2016 - 07/2017*
  * Designed a biomimetic sealing ring inspired by the functional surface of earthworm, which avoids rolling and distortion in
dynamic sealing with with service life increased by **33.5**% and **47.9**% compared to O- and rectangular-ring
  * Selected the Mooney-Rivlin model to describe the mechanical characteristics of rubber linings, and established two-dimensional
axisymmetric FEM of the biomimetic ring, groove, and slide bar based on the actual sealing setting to analyze Von-Mises
stress and contact stress

* ***<font color="#660000">Research and Development of Low-Shock Non-Explosive Separation Device</font>***                     
  * *Research Assistant, Supervised by Prof. Jian Wu*　　　　　　　　　　　　　　　　　                            
  * *Weihai, China; 12/2014 - 07/2015* 
  * Developed a Non-Explosive separation device to connect the launch vehicle and small satellite reliably and release the connection rapidly, and adopted divided nuts to the connect and separate bolt, the four-bar mechanism to control the movement
of releasing clamps (divided nuts), eight circumferentially distributed balls to lock the device, and the dual redundant DC
motors to unlock the device
  *  Generated Solidworks model, drawing and assemblies for the device, verified the bearing capacity by simulation and conducted the pre-stress modal analysis to avoid unlocking mistakenly by external vibration excitation in ANSYS, and simulated
the unlocking and separation process by ADAMS
  * Manufactured, assembled the parts, and tested the device's separation time and reliability in vacuum and low temperature environment

Selected Projects
======
 * ***<font color="#660000">Multifunctional Medical Nursing Bed</font>***
  * *Research Assistant, Supervised by Prof. Jian Wu*　　　　　　　　　　　　　　　　　                            
  * *Weihai, China; 07/2018 - 09/2018* 
  * Modified a commonly used manual nursing bed and added multi functions, such as anti-slip, easy dismantling and hemorrhoids prevention, promoted the blood circulation of the patient's legs and reduce the muscle atrophy caused
  * Analyzed the kinematics of the drive mechanism to make sure that the platform can cover the testing angle range and position accurately at a specific angle
  * [More details](http://zhengruitao.github.io/files/Nursing_Bed_Slide.pdf)
  
* ***<font color="#660000">End-actuator for Oil Tank Insulation-layer Surface Trimming and Its Process Planning</font>***
  * *Research Assistant, Supervised by Prof. Ming Chen*　　　　　　　　　　　　　　　　　　                       
  * *Shanghai, China; 09/2017 - 03/2018*
  * Designed a flexible end-actuator for insulation-layer surface trimming, including functions of distance measurement and radial feed adjustment, with the ability to control the thickness deviation between ±1mm for the diameter ranging from 2250 to 3350 mm
  * Proposed a collaboration method based on Support Vector Machine Regression to minimize the distance measurement error and used radial basis neural networks to compensate for the errors in different distance intervals
  * Planned the processing technology referring to bar turning, in which the eddy current displacement sensor determines the radial depth of cut, and the robot arm carries the end-actuator back and forth when the tank rotates around the axis
  * [More details](http://zhengruitao.github.io/files/End_actuator_Slide.pdf)
  
* ***<font color="#660000">Analysis and Experimental Study on Contact Characteristics of Aviation Sealing Profile</font>***
  * *Research Assistant, Supervised by Prof. Jinyang Xu*　　　　　　　　　　　　　　　　　　                        
  * *Shanghai, China; 11/2016 - 03/2017*
  * [Mirco surface morphology](http://zhengruitao.github.io/images/surface_morphology.tif) of the sealing profile is obtained by OLYMPUS optical digital microscope. Fractal characteristics were studied based on the structural function and fractal parameters were obtained The V-M function was employed to characterize the fractal surface, and the fractal contact model was established based on the single asperity contact model and area distribution function
  * A muliti-scale contact model of the sealing profile is developed based on the [finite element model](http://zhengruitao.github.io/images/compress_in_depth.jpg), and the contact characteristics of sealing profile in complex environment were studied: [micro particles](http://zhengruitao.github.io/images/micro_particles.tif) and [aging of material](http://zhengruitao.github.io/images/aging_of_material.tif)
  * Macro and micro contact characteristics of an aviation seal profile are investigated  by theoretical analysis, numerical simulation and experimental testing. And a new method for calculating the real contact area is proposed by coupling the theory and finite element method, which provides a reference for the design and application of seals
  
* ***<font color="#660000">Angle Measuring Platform for Fully Articulated Main Hub of Helicopter Rotor Systems</font>***
  * *Research Assistant, Supervised by Prof. Jian Wu*　　　　　　　　　　　　　　　　　                            
  * *Weihai, China; 05/2015 - 09/2016* 
  * Developed a platform to measure three angle parameters range for fully articulated main hub, which allows each blade to lead/lag (move back and forth in-plane), flap (move up and down about an inboard-mounted hinge), and feather (rotate about the pitch axis) independent of the other blades, implemented control system including user interface and query function, and reduced the whole measuring process from 3 hours to 40 minutes.
  * Analyzed the statics and kinematics of the drive mechanism using ANSYS and MATLAB, solved the stress of the main components and the coupling relationship between three angles, which iteratively update the design parameters to guarantee the structural strength of the platform, cover the required angle ranges and position accurately at specific angles
  * [More details](http://zhengruitao.github.io/files/Testing_Platform_Slide.pdf)
