# RobotBuilderStuff
 
 This repository contains the files necessary to use RobotBuilder.
 
## Extensions
 
 We've created a number of custom RobotBuilder extensions for the team to use. These extensions will be shown in the RobotBuilder pallette using icons with the CougarTech logo in them. The custom extensions allow you to select from a list of Java constants rather than raw integers when selecting things like a RoboRio port or pin number.
 
 If the custom extensions have not been installed on the laptop/PC that you are using, you'll need to copy all of the folders from the extensions folder on GitHub to the "extensions" folder under the "Robotbuilder" folder that was created when RobotBuilder was first installed. The local RobotBuilder extensions folder can be found at C:\Users\{username}\Robotbuilder\extensions. You'll need to restart RobotBuilder for the custom extensions to be used.
 
 Note: Any changes/updates to the extensions folder in the GitHub repository need to be copied back to the C:\Users\{username}\Robotbuilder\extensions folder for the changes to take effect since that's where RobotBuilder is started from.
 
## Template Files
 
 A set of template files have been created that the team can use as a starting point for a new robot project. CTRobotTemplate.yaml is the main file that RobotBuilder uses to store its project configuration. The CTRobotTemplate folder contains a Java robot project that mirrors what's stored in the CTRobotTemplate.yaml project file.
 
 To use the template files, copy the CTRobotTemplate.yaml file from GitHub into the FRCProjects folder that's created when RobotBuilder was installed. This folder can be found at C:\Users\{username}\FRCProjects. Copy the CTRobotTemplate folder from GitHub into the same FRCProjects folder.
 
 We need to rename the template files to something more meaningful. For example, rename the CTRobotTemplate.yaml file to "InfiniteRecharge.yaml" and the CTRobotTemplate folder to "InfiniteRecharge". Now you should have something like ..\FRCProjects\InfiniteRecharge.yaml and the folder ..\FRCProjects\InfiniteRecharge.
 
 Start VSCode and open the newly renamed folder (e.g. "InfiniteRecharge"). You'll see a few errors and that's to be expected because we need to rename a few things in the Java project. 
 
 In the project tree, you'll see an entry/node labeled "CTRobotTemplate". Right-click on the entry/node and rename it to your new project name (i.e., "InfiniteRecharge"). 
 
 There are still a few items in the project that need to be renamed. To do this, select "Replace in Files" from the VS Code Edit menu. Search for "CTRobotTemplate" and Replace that string with "InfiniteRecharge" or whatever you named your new project. There should be 11 occurrences in 7 files that get replaced. The code should build successfully now.
 
 Start RobotBuilder and open the newly renamed project file (e.g., "InfiniteRecharge.yaml"). In the folder tree, select the top folder "CTRobotTemplate". In the Properties Pane on the right, change "CTRobotTemplate" to "InfiniteRecharge".
 
 At this point you should be able to update your project by adding Subsystems, Commands, Inputs, Outputs, etc. and then generate code for your Java project.
 
 The template contains a Subsystem that is used for maintaining the system's constants called RobotConstants. There is also an XboxController object defined within the OI subsystem. All of the methods used by the "xbox" object are autogenerated by the custom XboxController extension.
 
 Good luck with your new robot project!!
 
## Documentation
 
 Link to the RobotBuilder docs: https://wpilib.screenstepslive.com/s/currentCS/m/robotbuilder
 
 
