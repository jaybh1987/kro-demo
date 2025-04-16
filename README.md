
- Here platform team provide a `ResourceGraphDefinition` (`RGD`) for the teams.  
Developers from the different teams can use this `RGD` to deploy their application.
Which means platform team has full control on each parameters configured by the team. No new configurations can be added by team unless platform team update the `RGD`


- As we are using `RGD` we can avoid patching files. However, we will have only 1 file to manage. 

- Still `base/overlay` directory structure we can use, base contains the `RGD` and overlays providing values as per their requirements. 
