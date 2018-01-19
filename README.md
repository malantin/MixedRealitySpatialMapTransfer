# Mixed Reality Spatial Map Transfer
This sample put together the necessary parts of the Mixed Reality Toolkit to capture a mesh with a HoloLens device, transfer the mesh via local network to a PC and display that mesh using a Mixed Reality Immersive Headset.

In order to run the solution:
- You need to set the correct IP address and port for the Desktop MR application
- Launch the Hololens.Scanner on the HoloLens
- Scan the room
- Start the Immersive Mixed Reality App (Immersive.Viewer) in Unity on your PC
- Press the Key for Network mesh loading on the PC (Default is N)
- Send the Mesh with the command "Send meshes"
- You can save the mesh using the S key on your PC and load the saved mesh using the L key

Check [https://github.com/Microsoft/MixedRealityToolkit-Unity/tree/master/Assets/HoloToolkit/SpatialMapping](https://github.com/Microsoft/MixedRealityToolkit-Unity/tree/master/Assets/HoloToolkit/SpatialMapping) for more insights on remote mapping with the MR toolkit.
