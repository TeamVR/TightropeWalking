Vive IK Demo README

Please follow these steps:

0. Room Setup
	The most important thing is to calibrate floor accurately, preferably in standing mode.
1. Enter height:
	Enter the player's height in height_config.txt in meters. For example, if the player's height is 160 centimeters, enter 1.6. If the config file is deleted, the program will revert to default height 1.75.
2. Run vive_ik_demo.exe
3. Attach the trackers:
	Bind one tracker to each foot. See tracker_setup_foot.jpg.
	Bind one tracker to the waist or belly. See tracker_setup_torso.jpg.
	For more details, refer to the documentation "Full Body Motion Capture Using Vive Tracker".
4. Walk to the position of Lena:
	Find Lena and walk to her place so that your bodies overlap. Most importantly, step on her feet. You can find you feet in VR by refering to the white cubes, which are markers for the trackers.
5. (Important)Raise your hands above the tracker you put on your waist. Then press Grip button on the controller twice.
6. Now you can walk, lift your hand, twist your waist etc in VR. You can look downward, or you can look into the mirror in front of you.

Note: The program assign trackers/controllers by height. The two highest devices will be hands, the third one be torso, the lowest two are feet.

