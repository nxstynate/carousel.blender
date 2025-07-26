
# 🎠 Blender Collection Instance Animator 🎠

## 🚀 Elevate Your Animations!

Tired of manually animating collection instances? This Blender addon is your new best friend! 🥳

The **Collection Instance Animator** simplifies the process of creating stunning carousel-style animations. It allows you to apply sequential Z-axis keyframe animations to linked collection instances in a target `.blend` file, all from a user-friendly panel in your current workspace.

## ✨ Features

*   **Scan & Go:** Automatically scan a target `.blend` file for linked collection instances.
*   **Intuitive UI:** A clean and simple panel in the 3D View's sidebar for easy access.
*   **Flexible Animation Control:** Customize your animations with parameters like start frame, Z-axis values, hold duration, frame offsets, and overlap.
*   **Batch Operations:** Select all or none of the collection instances with a single click.
*   **Safe Workflow:** The addon works on a target file, leaving your current file untouched. It also automatically saves the changes in the target file.

## 💾 Installation

1.  **Download:** Grab the `carousel.py` file.
2.  **Open Blender:** Launch Blender (requires version 3.0.0 or newer).
3.  **Install the Addon:**
    *   Go to `Edit > Preferences`.
    *   Click on the `Add-ons` tab.
    *   Click the `Install...` button at the top right.
    *   Navigate to where you saved `carousel.py` and select it.
4.  **Enable the Addon:**
    *   In the Add-ons tab, search for "Collection Instance Animator".
    *   Check the box next to the addon's name to enable it.

You're all set! The addon's panel will now be available in the 3D View.

## 📖 How to Use

1.  **Open Your Working File:** Start with the Blender file where you want to control the animation from.
2.  **Locate the Panel:** In the 3D View, press the `N` key to open the sidebar. You'll find a new tab called **"Collection Animator"**.
3.  **Select Target File:**
    *   Click the folder icon in the "Target File" section.
    *   Browse and select the `.blend` file that contains the linked collection instances you want to animate.
4.  **Scan for Collections:**
    *   Click the **"Scan Target File"** button.
    *   The addon will scan the file and populate the "Collection Instances" list.
5.  **Select Collections to Animate:**
    *   Check the boxes next to the collection instances you want to include in the animation.
    *   Use the "All" and "None" buttons for quick selections.
6.  **Set Animation Parameters:**
    *   Adjust the animation settings to get the desired effect.
7.  **Apply Animation:**
    *   Click the **"Apply Animation to Target File"** button.
    *   The addon will open the target file in the background, apply the Z-axis keyframes to the selected collection instances, and save the file.

## ⚙️ Animation Parameters

*   **Start Frame:** The frame where the entire animation sequence begins.
*   **Z In-frame Value:** The Z-axis position of the collection instance when it's visible in the frame.
*   **Z Out-of-frame Value:** The Z-axis position of the collection instance when it's hidden.
*   **Hold Duration:** The number of frames the collection instance stays in the "in-frame" position.
*   **Frame Offset:** The number of frames between the start of one collection's animation and the next.
*   **Overlap:** The number of frames that one collection's animation overlaps with the next, creating smoother transitions.

## ⚠️ Important Note

This addon will **automatically modify and save the target `.blend` file**. Make sure you have a backup of your target file if you want to preserve its original state.

---

Happy animating! ✨
