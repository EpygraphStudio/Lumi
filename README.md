https://github.com/user-attachments/assets/00bcc686-96f8-4609-87f9-2737803debdd

# Lumi
Lumi is a Unity Engine light detector, created to facilitate stealth and horror genre games.

The script works best with URP and the sample scene is also set up in URP.

## Features
* Supports Directional, Point, and Spot realtime lights.
* Baked light support via light probes and lightmaps.
* Accounts for perceived brightness from coloured lights.
* Runs in editor for quick iteration.
* Multiple sample points per detector.
* Two sample point evaluation modes - Average and Max.
* Disable Updates and manually update when needed.

## Screenshot
![LumiDemo](https://github.com/user-attachments/assets/7236dc5c-821a-4696-9ff8-eac1585ed5f6)

## Limitations
* Since realtime lights use ray casting, shadow caster mesh colliders need to be accurate.
* Does not account for soft shadow edges - a sample point is either in shadow or not.
* Cannot account for screenspace Global Illumination solutions.




