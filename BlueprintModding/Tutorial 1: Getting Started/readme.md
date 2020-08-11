# **Tutorial 1: Getting Started**

## 1. Setup

[UE4 Official Website](https://www.unrealengine.com/en-US/get-now)

Install Unreal Engine 4. Download the UE4 launcher from the web page provided. In the launcher navigate to __Library__. At the top should be a section called 'Engine Versions'. Press the '+' button. A new engine version selector will appear. Click the drop down arrow with the version and select version '4.22.x'. Then install the engine.

![DRG BP Modding Tutorial 1 Step 1](https://i.imgur.com/ICOMFQ4.jpg)

## 2. Create the Project

Now launch UE4, making sure version '4.22.x' is selected. The __Unreal Project Browser__ will appear. Go to __New Project__ -> __Blueprint__ -> __Blank Project__. Do NOT include starter content.

Set the __Project Name__ to 'FSD'. Confirm with the image below and then press 'Create Project'.

![DRG BP Modding Tutorial 1 Step 2](https://i.imgur.com/qhnzghk.jpg)

## 3. Install Content Folder Hierarchy

Download the 'Empty Content Hierarchy' from our discord. [Visit EmptyContentHierarchy](https://discord.com/channels/741506916051845121/741509297497964637/742459574505832468)

Next, close Unreal Engine 4 if it is still open. Navigate to your new Unreal Engine 4 project folder. It should be named 'FSD'. Inside 'FSD' should be another folder named 'Content'. Open the content folder and delete everything inside.

Extract the 'EmptyContentHierarchy' zip file you previously downloaded to a different location. Navigate to the sub-folder 'Content' within the extracted folders. Copy ALL of the folders inside.

Paste them in the 'Content' directory of your __UE4 Project__.

You should now have something like this:

![DRG BP Modding Tutorial 1 Step 3](https://i.imgur.com/nYfjHyk.jpg)

## 4. Verify

Now launch UE4 (4.22.x) and open your UE4 Project, FSD.

If everything is correct, your content browser in UE4 should look like this:

![DRG BP Modding Tutorial 1 Step 4](https://i.imgur.com/JvHt45U.jpg)

## 5. Final Preparation

Navigate to __File__ -> __Package Project__ -> __Packaging Settings__.

Set the __Build Configuration__ to 'Shipping'. Then, uncheck the option for 'Use Pak File'.

![DRG BP Modding Tutorial 1 Step 5](https://i.imgur.com/001Z9oE.jpg)

## 6. Complete

Your UE4 Project is now complete and ready for the next steps.
