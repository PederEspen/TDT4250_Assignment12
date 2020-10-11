# TDT4250_Assignment1_2

For this assignment I have co-operated with Eskild Brobak: eskildbr@stud.ntnu.no

Decisions

We decided to not include any semesters in the assignment, because in the first assignment we included years which contains two semesters. We did not change the model from the first assignment either, because it worked and it did show the information we wanted to present. However, we now see that it would be better to include semesters for the model so that the information about subjects and semesters is more presentable and clear, and so that it more closely resembles the main 
HOW-TO:

Clone the repo
1. Open Eclipse and go to File -> open project from file system
2. Press Archive and then first open Assignment12-TDT4250 folder
3. Same as step 3. but now open org.eclipse.acceleo.module.sample
4. Navigate to the src folder in org.eclipse.acceleo.module.sample
5. Navigate to "Transformation.mtl" file inside the org.eclipse.acceleo.module.main folder
6. Right click on "Transformation.mtl" file and select Run as "launch acceleo application"
7. Choose a model, which should be either one of the following programmes: BachelorInformatics.xmi, MasterInformatics.xmi or IntegratedMasterDataSience.xmi
8. Choose a target, which should be the src folder in the org.eclipse.acceleo.module folder
9. Hit apply and run.
Note: Remember to delete the HTML files so that you see that it actually works.

We had much trouble with a file that for some reason just dissapears when cloning the repo. If you get a error message that says that you do not have the "transformation.emtl" file:

1. Open up terminal and type in "git restore org.eclipse.acceleo.module.sample/bin/org/eclipse/acceleo/module/sample/main/Transformation.emtl"

2. Start from point 7. in the HOW-TO list

3. Manually download the file from this repo. Should be found inside org.eclipse.acceleo.module.sample/bin/org/eclipse/acceleo/module/sample/main folder

4. Put the missing file in org.eclipse.acceleo.module.sample/bin/org/eclipse/acceleo/module/sample/main folder

