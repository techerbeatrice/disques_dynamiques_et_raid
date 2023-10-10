# Disques dynamiques et RAID sur Windows
___

Prérequis :  
une VM avec windows     
4 disques en tout dont :   
1 disque (toujours non dynamique) pour le système de windows   
3 disques dynamiques    

______

Distinction entre différents niveaux de RAID :   

![image](https://github.com/techerbeatrice/disques_dynamiques_et_raid_sur_Windows/assets/138071140/317ccbd7-ce11-4afe-b5d6-7bc492a35c25)
Minimum 2 disques durs, volume agrégé par bandes, striping. Le point faible de RAID 0, si un disque dur connaît une défaillance, l’ensemble des données est perdu.   

![image](https://github.com/techerbeatrice/disques_dynamiques_et_raid_sur_Windows/assets/138071140/15379ac9-2d68-4a54-b9e4-b01b9721d6e8)
Miroir, mirroring. RAID 1 offre une fiabilité d’autant plus excellente, les données vont être stockées plusieurs fois sur des disques différents.    

![image](https://github.com/techerbeatrice/disques_dynamiques_et_raid_sur_Windows/assets/138071140/28d4fead-0f3f-453b-9df1-5a7c8f845d52)
Minimum 3 disques durs, architecture permettant de bénéficier des avantages de RAID 0 et de RAID 1.

____

**Installer un RAID 1 avec 2 disques de même taille**     

![image](https://github.com/techerbeatrice/disques_dynamiques_et_raid_sur_Windows/assets/138071140/d0497b81-cd8d-4c8e-b8fc-c8a03d2de8a9)

---

![image](https://github.com/techerbeatrice/disques_dynamiques_et_raid_sur_Windows/assets/138071140/0421bb1c-7b41-4572-bc35-e10313395cf0)

---

![image](https://github.com/techerbeatrice/disques_dynamiques_et_raid_sur_Windows/assets/138071140/98683dcf-0eb1-44e0-8f66-02d2e277fb6e)

