# Netlogo_phishing_model
This is a simulation of phishing attack on an enterprise

## WHAT IS IT?

This model is intended to represent a phishing attack on an enterprise/company. The goal of the model is to show importance of phishing awareness among employees. Model shows as well key players: hackers (red hats) who attack and infosec department (blue hats) who will defend. Almost always if one employee account is hacked = all the ecosystem is hacked as well.

## HOW IT WORKS

Each time step (tick), hacker(s) - the red big person figure, is trying to attack employees of the company we create. Employee can be created either aware of cyber attacks or not-aware, e.g., vulnerable. The vulnerable employees (orange) are the first to be attacked by hackers. In the contrary, the aware employees (white) are immune to attacks, but will get hacked once other employees are hacked.

## HOW TO USE IT

Using the sliders, choose the NUMBER-OF-EMPLOYEES and the NUMBER-OF-CONNECTIONS (links between employees).

The NOT-AWARE-EMPLOYEEES slider determines how many of the employees will be vulnerable to attacks from the beginning. It means they will be first to get hacked.

The NUMBER-OF-HACKERS is custom and represents amount of hackers in the simulation. They are displayed as red larger person figures.

The NUMBER-OF-BLUE-HATS is custom and represents the amount of employees in indosec department. They are displayed as blue larger person figures.

Then press SETUP to create the simulation of a company.  Press GO to run the model.  The model will not run if all the employees are aware and immune to attacks.

Employees will try to recover from being hacked, but it wouldn't give any results unless we increase awareness of users (slider not-aware-emploees to 0).

The SECURITY STATUS plot shows the number of employees in each state (not-aware, hacked and aware) over time.


## THINGS TO TRY

- Set speed to slow and let only one employee be unaware of the security rules (vulnerable). 

- Set 0 unaware employees, they will all turn white.

## EXTENDING THE MODEL

Indeed it would be more interesting to see a more exciting battle between attackers and defenders, but the truth is: hackers need only one chance to exploit all the system and defenders should defend it every single time and make sure all the employees follow strict security rules.


## RELATED MODELS

Virus, Disease, Preferential Attachment, Diffusion on a Directed Network

## NETLOGO FEATURES

Links are used for modeling the network.  The `layout-spring` primitive is used to position the person figures and links such that the structure of the network is visually clear.

Though it is not used in this model, there exists a network extension for NetLogo that you can download at: https://github.com/NetLogo/NW-Extension.

## HOW TO CITE

If you mention this model or the NetLogo software in a publication, we ask that you include the citations below.

For the model itself:

* Tukhvatullina K. (2021). Netlogo Hacking Attack/Phishing Simulation on an Enterprise Level.

## THIS MODEL WAS INSPIRED BY

* Stonedahl, F. and Wilensky, U. (2008).  NetLogo Virus on a Network model.  http://ccl.northwestern.edu/netlogo/models/VirusonaNetwork.  Center for Connected Learning and Computer-Based Modeling, Northwestern University, Evanston, IL.

Please cite the NetLogo software as:

* Wilensky, U. (1999). NetLogo. http://ccl.northwestern.edu/netlogo/. Center for Connected Learning and Computer-Based Modeling, Northwestern University, Evanston, IL.

## COPYRIGHT AND LICENSE

Copyright 2008 Uri Wilensky.

![CC BY-NC-SA 3.0](http://ccl.northwestern.edu/images/creativecommons/byncsa.png)

This work is licensed under the Creative Commons Attribution-NonCommercial-ShareAlike 3.0 License.  To view a copy of this license, visit https://creativecommons.org/licenses/by-nc-sa/3.0/ or send a letter to Creative Commons, 559 Nathan Abbott Way, Stanford, California 94305, USA.

Commercial licenses are also available. To inquire about commercial licenses, please contact Uri Wilensky at uri@northwestern.edu.

<!-- 2008 Cite: Stonedahl, F. -->
