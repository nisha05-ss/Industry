# Project Requirements

## Project

**AR-Based Smart Machine Monitoring System Using Unity**

This file documents the software and project components identified in the project materials.

## Core Technologies

### Unity
Used for:
- AR application development
- 3D scene integration
- AR camera configuration
- Machine animation integration
- Android application preparation

### Vuforia
Used for:
- AR camera functionality
- Target recognition
- Placing the 3D visualization using the recognized target

### Blender
Used for:
- Processing the industrial 3D model
- Reducing/optimizing the large model
- Creating/modifying machine animations
- Preparing assets for Unity

### Android
Used as the mobile deployment platform for the final AR application.

## Project Assets

The project requires:

- Industrial 3D plant model
- Machine models/components
- AR reference target
- Materials/textures
- Machine animations
- Unity scenes
- Unity scripts, where applicable
- Vuforia configuration/assets
- Android build configuration

## Model Size Consideration

The project documentation states that the original 3D model was approximately **5 GB**.

Because of the large size, the model was processed and optimized using Blender before being imported into Unity.

Do not commit the original 5 GB model directly to the normal Git repository.

## Testing Requirements

The final application should be tested for:

1. Mobile camera initialization
2. AR target recognition
3. 3D plant placement
4. Plant and machine visualization
5. Machine animation
6. Android APK execution

## Repository Notes

The exact Unity editor version, Vuforia package version, Android SDK version, device model, and hardware specifications were not specified in the supplied project document.

Add those exact versions here after verifying them from the actual development environment:

```text
Unity Version:          TODO
Vuforia Version:        TODO
Blender Version:        TODO
Android SDK/API:        TODO
Test Device:            TODO
Minimum Android Version: TODO
```

Do not replace these values with guessed versions.
