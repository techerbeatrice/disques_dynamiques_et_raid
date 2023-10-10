# Disques dynamiques et RAID sur Windows
___

Prérequis :  
une VM avec windows server 2022   
4 disques en tout dont :   
1 disque (non dynamique) pour le système de windows   
3 disques dynamiques    

______

Distinction entre les différents RAID :   

![image](https://github.com/techerbeatrice/disques_dynamiques_et_raid_sur_Windows/assets/138071140/317ccbd7-ce11-4afe-b5d6-7bc492a35c25)
volume agrégé par bandes, striping. Le point faible de RAID 0 est la fiabilité. Si un disque dur connaît une défaillance, l’ensemble des données est perdu.   

![image](https://github.com/techerbeatrice/disques_dynamiques_et_raid_sur_Windows/assets/138071140/15379ac9-2d68-4a54-b9e4-b01b9721d6e8)
miroir, mirroring. RAID 1 offre une fiabilité d’autant plus excellente que le nombre de disques durs constituant la grappe est important.
