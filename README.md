# Gesture Tracker

Prefab using [contact trackers](https://github.com/VRLabs/Contact-Tracker) with some additional proximity sensors to determine if a player is doing any of the default gestures and drive parameters based on that.

## **Installation**
[Video](https://youtu.be/cCnQug_tGXs)

- Drag the "Gesture Tracker" prefab into the heirarchy  
- Right click on the prefab to unpack it and then drag it onto the base of your avatar  
- Select all objects that start with "Left" and drag in your right wrist bone into the empty source on the parent constraint  
- Select all objects that start with "Right" and drag in your left wrist bone into the empty source on the parent constraint  
- Merge the provided FX controller with yours using the [VRLabs Avatar 3.0 manager](https://github.com/VRLabs/Avatars-3.0-Manager)  
- Set WD settings according to your animator  
- Create a toggle in your menu to enable the system   

## **How to use**
Place your hands into the hands of another player and enable the system.  
>Ensure that the other player is making a fist gesture during calibration for best results. They must not open their hand, loosen their grasp, or do a peace sign until the indicator on their hand dissapears. 

## **How it works**
[Video](https://youtu.be/dhVPa6VImDc)  
-  Basically Proximity sensors measure distance between contacts and use that information to drive parameters.

## **Download**
[Latest release](https://github.com/ThatFatKidsMom/Gesture-Tracker/releases/tag/1.0.0)

## **Credit**
[VRLabs](https://github.com/VRLabs)  
[Freepik](https://www.flaticon.com/authors/freepik)

## **License**
[MIT](https://github.com/ThatFatKidsMom/Gesture-Tracker/blob/main/LICENSE)

## **Contact**
If you need help with something you can message me on discord at ThatFatKidsMom#6462
