# Bedlam Fringe Show file
 Blank Show File, Rig Plan, and VWX Model of the Bedlam Theatre for the uses of Bedlam Fringe 2025

Link to EOS Show file: [Click Here](https://github.com/leon0241/Bedlam-Fringe-Showfile-25/blob/main/ETC%20EOS/Bedlam%20Fringe%20Blank%20Showfile%20V1.3%202025-07-24%2015-05-52.esf3d)

Link to MVR/Capture Model: [Click Here](https://github.com/leon0241/Bedlam-Fringe-Showfile-25/blob/main/MVR/bedlam-fringe.mvr)

Link to Rig Plan: [Click Here](https://github.com/leon0241/Bedlam-Fringe-Showfile-25/blob/main/PDFs/Bedlam%20Fringe%202025%20Rig%20Plan%20V1.3.pdf)

## How to Import MVR
From EOS Browser, Import > MVR/Capture Model > [Browse to the file]. Map Devices, keep Overwrite ticked, and press OK. Note: Delete Channels 55 and 56 from the patch after you import, it will create a ghost fixture that is still on the augment3d but the actual fixture data has been moved to channels 71 and 73 (to acccount for the new CS ML spot)

If you have recorded cues with the ignites, then you can copy all the data with Channel X Copy to Channel Y {Plus Show} hotkey.

You will likely need to *Map Devices* for this to work, which is where you link the MVR devices with the EOS Fixture profiles. To use this:
- Click the MVR Fixture from Source File tab, and find a corresponding EOS Fixture in the browser on the left.
- Click the *Link Devices* Button on the left.
- Your new fixture link is now shown on the right
A list of the DMX Maps are as follows:

## EOS Magic Sheet

<p float="left">
  <img src="/images/Bedlam Fringe Blank Showfile V1.4 - Magic Sheet 1 - Rig Plan.png" width="33%" />
  <img src="/images/Bedlam Fringe Blank Showfile V1.4 - Magic Sheet 2 - ML Controls.png" width="33%" /> 
  <img src="/images/Bedlam Fringe Blank Showfile V1.4 - Magic Sheet 3 - LED Wash.png" width="33%" />
  <img src="/images/Bedlam Fringe Blank Showfile V1.4 - Magic Sheet 4 - FX Controls.png", width="33%" />
  <img src="/images/Bedlam Fringe Blank Showfile V1.4 - Magic Sheet 5 - Effects.png", width="33%" />
  <img src="/images/Bedlam Fringe Blank Showfile V1.4 - Magic Sheet 6 - Prog Utility.png", width="33%" />
</p>

------
| MVR | EOS |
| - | - |
| Light SFX Kinetic Lights Mirror Sphere 40 | Mirror Ball |
| BeamZ Ignite400 | Ignite 400 |
| Chauvet Intimidator Spot LED 350 | Indimidator Spot LED 350 14ch |
| Chauvet Rogue R2X Wash | Rogue R2X Wash 22ch |
| Martin MAC TW1 | TW1 80V Extended (20ch) |
| Prolights StudioCOB FC 150 | Studio COB FC 8ch |
| Stairville Show Bar TriLED 18x3W RGB | Show Bar Tri 18x3W 5ch |
| Stairville Wild Wash 132 LED RGB | Wild Wash 132 LED RGB 6ch |

Generics are just mapped as generic dimmers, but ETC fixtures like the Source 4 PAR or Jr have their own fixture profile if you want to be specific.

## Profiles
- 41 is a SR Spot, free first 3 weeks and priority to Love You, Bye in the 4th.
- 42 is a SR Spot, free first 3 weeks and priority to Love You, Bye in the 4th.
- 43 is a CS Spot, priority to What We Carry, and Perfect Dead Girls 
- 44 is a CS Spot, priority to Sins of the Mother, and Love You, Bye
- 45 is a CS Spot, priority to the Improverts
- 301 - 303 are batten lights that are used specifically for Perfect Dead Girls

## Changelog
- Added a Martin MAC TW1 CS Profile. Keep in mind this has pretty bad zoom we've found
- Added more profiles and priority list
- Orientations of ML spots have been adjusted and should be accurate to the venue. Import the MVR if you have already started pre-programming
