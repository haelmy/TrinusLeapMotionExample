# Unity Trinus and Leap Motion Example

## Usage

### Using the package (recommended)

 1. Create a new unity project (or use an existing one you want to add Trinus and Leap Motion to)
 2. Register for a Leap Motion Developer account, download the [Leap Motion Orion Unity Package](https://developer.leapmotion.com/unity) and import the package into your project.
 3. Install the [Trinus SDK from the Assets Store](https://www.assetstore.unity3d.com/en/#!/content/57952).
 4. Import the [package of this project](https://github.com/haelmy/TrinusLeapMotionExample/releases).

### From source

I think there might be a problem with using checking out this code and using it right away, since Unity messes up connection of non existing Prefabs, when they are missing and importing them afterwards does not seem to fix it. So some things will have to be rewired, if one uses the source project.

### Adjustments

You might want to adjust the position of the `LeapHandController` (in the `TrinusCamera`) to match the distance of your Leap Motion to the center of your phones screen when mounted in the Cardboard HMD.
