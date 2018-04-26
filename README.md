# Mixed Reality Spatial Map Transfer
This sample put together the necessary parts of the Mixed Reality Toolkit to capture a mesh with a HoloLens device, transfer the mesh via local network to a PC and display that mesh using a Mixed Reality Immersive Headset.

In order to run the solution:
- You need to set the correct IP address and port for the Desktop MR application in both Unity projects
- Build the Hololens.Scanner and deploy to your HoloLens device
- Launch the Hololens.Scanner on the HoloLens
- Scan the room
- Build and deploy the Immersive Mixed Reality App (Immersive.Viewer) on your Windows Mixed Reality capable PC
- Send the Mesh with the voice command "Send meshes" on your HoloLens
- You can save the mesh using the S key on your PC and load the saved mesh using the L key

When saving a mesh from Unity Editor, it will be located in a folder like this:

"C:\Users\username\AppData\Local\Packages\Immersive.Viewer_pzq3xp76mxafg\RoamingState\roombackup.room"

![MR Mesh Preview](./Images/ImmersivePreview.png)

Check [https://github.com/Microsoft/MixedRealityToolkit-Unity/tree/master/Assets/HoloToolkit/SpatialMapping](https://github.com/Microsoft/MixedRealityToolkit-Unity/tree/master/Assets/HoloToolkit/SpatialMapping) for more insights on remote mapping with the MR toolkit.
