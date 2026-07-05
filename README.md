<img src="assets/Brake_Aid_Logo.png" alt="Brake Aid logo" width="200">

# Brake Aid Sim Edition
### Real-Time Sim Racing Companion App<br>

<p align="center">
<img src="assets/Brake_Aid_iRacing_Screenshot.png" alt="Brake Aid being used with iRacing" width="800">
</p>

 "In racing there are always things you can learn, every single day. There is always space for improvement, and I think that applies to everything in life." - Lewis Hamilton<br>

### Do you know when to brake?<br>Do you brake too early or too late?<br>And most importantly, do you brake consistently?<br>



### Knowing When To Brake

Braking is one of the most critical elements of race driving, directly influencing lap time, consistency and overall vehicle control.<br>
Knowing **when** to brake—and doing so consistently—is what separates confident, fast drivers from the rest.<br>

Brake too late and you risk overshooting the corner. Brake too early and you sacrifice valuable speed all the way to the next straight.<br>

Brake Aid helps remove the guesswork by providing intelligent, dynamic braking references that adapt to the conditions of each corner.<br>
Rather than relying on fixed trackside markers, Brake Aid calculates when to brake based on your current approach speed and a braking dataset developed for the specific game, track and vehicle combination.<br>

Whether you're learning a new circuit or refining the final few metres of your braking points, Brake Aid helps you build confidence, improve consistency, and focus on driving—one corner at a time.

### Why Brake Aid?

Brake Aid combines adaptive telemetry analysis with shareable braking datasets to deliver intelligent, real-time braking guidance for supported sim racing titles.<br>

Experienced drivers can create and refine braking datasets using Brake Aid's adaptive learning mode, then export complete collections covering multiple game, track and vehicle combinations.<br>

These dataset collections can be shared with other Brake Aid users, allowing them to immediately benefit from proven braking references without first completing a benchmark lap.<br>

Every braking marker remains fully customisable. Drivers can fine-tune individual corners in precise two-metre increments while preserving the integrity of the original dataset, allowing each driver to gradually tailor the braking references to suit their own driving style.<br>

When required, Brake Aid can seamlessly switch back into Adaptive Mode, allowing new braking events and changing driving performance to be incorporated into an updated braking dataset before returning to Dataset Hold Mode.


## Overview

- Import and use braking datasets created and refined by experienced Brake Aid users.
- Export and share complete collections of braking datasets covering multiple game, track and vehicle combinations.
- **Adaptive Mode** analyses your driving performance and continually generates updated dynamic braking datasets as your driving evolves.
- **Dataset Hold Mode** preserves a braking dataset indefinitely while allowing individual brake markers to be personalised using per-corner distance offsets.
- Switch seamlessly between **Adaptive Mode** and **Dataset Hold Mode** at any point during a driving session.
- Dynamic brake markers automatically compensate for changes in approach speed to deliver consistent corner entry performance.
- Brake markers are communicated using Brake Aid's on-screen **anticipation light**, providing a clear one-second braking cue before the calculated braking point is reached.
- Fine-tune individual braking markers in precise two-metre increments using user-configurable controls.
- The **Don't Count Lap** function prevents an unrepresentative lap from replacing your current braking dataset.
- Save and resume braking datasets for every supported game, track and vehicle combination.
- Multi-user support with independent driver profiles and braking datasets.


## Shared Braking Datasets

Brake Aid introduces a new way of learning race circuits.

Experienced Brake Aid users can create, refine and export complete collections of braking datasets covering multiple supported games, tracks and vehicles.

These collections can be shared with other drivers, allowing them to immediately begin using proven braking references instead of building every braking dataset from scratch.

Imported datasets remain fully customisable. Individual brake markers can be adjusted to suit your own driving style while preserving the overall structure of the original dataset. When additional refinement is required, simply switch to Adaptive Mode to allow Brake Aid to generate an updated dataset based on your own driving performance.


## Supported Games
- iRacing
- Assetto Corsa

## System Requirements
- Operating System: Windows 10 or Windows 11 (64-bit)
- Supported sim racing game installed on the same PC (see list above)
- Hardware: PC must meet the minimum system requirements for the supported sim racing game you intend to use
- Runtime Dependencies: All required application runtime files are included with this release (no separate Visual C++ installation normally required)
- .NET Framework: Microsoft .NET Framework 4.8 or later (included by default on most Windows 10/11 systems)
- Storage: At least 20MB free space for this add-on.
- Permissions: Administrator privileges may be required for initial setup or certain hardware / integration features

#### Notes:
- This software is an add-on and requires a compatible supported sim racing game to function.
- Performance is primarily dependent on the host game’s system requirements rather than this add-on itself
- Windows 10/11 Home and Pro are supported; other editions may work but may not be officially tested
- For best compatibility, keep Windows and supported game installations up to date

## Quick Start
1. Download the latest release from the Releases page  
2. Extract the ZIP to a desired folder on your PC
3. Run Brake Aid Beta.exe  
4. On the setup interface, click *Button Mapping* in the left pane and map Brake Aid's functions to either keyboard keys or physical buttons on your sim hardware.
5. *(Optional but recommended)* Import an external Brake Aid dataset collection created by an experienced driver.
6. Click *Brake Aid Setup* on the left pane, create a new user, then click *NEXT* on the bottom right.
7. Launch a supported sim racing title.
8. Start a race session (which will prompt the Brake Aid interface to reappear)
9. Choose one of the available session options (this will cause the interface to minimise to the system tray):
   - **Start with External Dataset**
   - **Resume with Your Previous Dataset**
   - **Start New Session (Adaptive Mode)**<br>
     #### Note: If *Start New Session (Adaptive Mode)* has been selected, you will complete a *benchmark lap*  first, where Brake Aid will analyse your driving to generate an initial braking dataset (no dynamic brake markers are provided for the benchmark lap)
10. Drive using Brake Aid's real-time anticipation light guidance.
11. Personalise individual braking markers as required using the offset controls, or switch to Adaptive Mode to further develop the braking dataset.<br><br>



### Windows Defender SmartScreen Notice

Because Brake Aid is currently distributed as an unsigned public beta application, Windows Defender SmartScreen may display a warning when launching the software for the first time.

This is expected behavior for newly distributed applications that have not yet established Windows reputation/signing trust.

#### If Windows Displays “Windows protected your PC”
- Click **More info**
- Click **Run anyway**

You may need to do this **once** on first launch for both:

Brake Aid Beta.exe<br>
BrakeAidCore.exe (see below)<br>

#### If the Brake Aid UI Interface Opens But The Software Does Not Function Correctly

Windows may have blocked Brake Aid's backend component (BrakeAidCore.exe) from starting.<br>
(You can verify whether the backend component is running by checking whether the Brake Aid icon is present in the Windows system tray.)

To resolve:
1. Close the Brake Aid UI Window (if open)
2. Open the Brake Aid root folder (the extracted ZIP)
3. Navigate to the **Core Files** directory
4. Manually launch **BrakeAidCore.exe**
5. If prompted by Windows SmartScreen:
- Click **More info**
- Click **Run anyway**<br><br>
The backend may immediately close after manual launch — this is normal
6. Launch **Brake Aid Beta.exe** again normally — Brake Aid should now launch with full functionality.
  

## Beta Access / License Token

Brake Aid is currently free to use during beta.

Each release includes a time-limited beta license token that enables full functionality until its expiry date (shown in the **ABOUT** tab of the setup interface).<br>
Once a token expires, the software will no longer function until an updated public beta token is downloaded from this repository.<br>
Updated beta tokens will be made available through this repository.

### Updating the license token
- Download the latest license token (BALicense.lic) from [here](https://raw.githubusercontent.com/BrakeAid/sim/main/beta-license-token/BALicense.lic)
- Ensure the Brake Aid application is fully closed (check the system tray!)
- Navigate to the *Brake Aid License* sub directory within the Brake Aid root folder.
- Copy/move the updated license token file, *BALicense.lic* into this directory (overwrite the existing license token file, if present)
- Launch the Brake Aid application again and check the **ABOUT** tab to confirm the license token has been successfully applied.

## Full User Guide

For detailed setup, feature explanations and troubleshooting, see the full *Brake Aid User Guide* PDF available [here](docs/Brake%20Aid%20User%20Guide.pdf)

## Support, Feedback & Beta Community

Join the official Brake Aid Discord community for beta support, troubleshooting, compatibility discussion, bug reporting, and feature requests.


### Join the Discord
[Official Brake Aid Beta Discord](https://discord.gg/ESt7pu5yyD)

### Discord Channels Include:
- General Discussion
- Bug Reporting
- Feature suggestions and general feedback
- Troubleshooting



## Legal / Terms

### Beta Status
This software is currently distributed as a beta release and may contain bugs, incomplete features, or changes between versions.

### Usage
This beta software is currently provided free of charge for evaluation and testing purposes.

### Redistribution
You may not redistribute, mirror, or repackage this software or its associated license tokens without permission.

### Proprietary Software
This software is proprietary and closed-source. Unauthorized modification or reverse engineering is prohibited.

### No Warranty
This software is provided "as is" without warranty of any kind. Use at your own risk.<br><br>

© 2026 Vertech Hume International Pty Ltd. All rights reserved.

