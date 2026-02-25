# Minecraft PFP Generator

Welcome to the Minecraft PFP Generator! This simple web tool allows you to create custom profile pictures using your Minecraft username or by uploading your own skin.

## How it Works

The generator provides an easy way to get a unique profile picture with a custom background.

1.  **Input Your Username:** Enter your Minecraft username into the designated field.
2.  **Load Skin:** Click the "Load Skin" button. The generator will fetch your Minecraft skin from online services.
3.  **Customize Background:**
    *   **Predefined Gradients:** Cycle through a selection of predefined background gradients using the left and right arrow buttons.
    *   **Custom Gradient:** Check the "Use Custom Gradient" box to reveal color pickers. You can then select two custom colors to create your own unique gradient background.
4.  **Skin Customization:**
    *   **Revert Skin Horizontally:** This option flips your skin horizontally on the PFP.
    *   **Transparent Background:** If selected, your PFP will have a transparent background instead of a gradient.
5.  **Download PFP:** Once you are happy with your creation, click the "Download PFP" button to save your profile picture as a PNG image.

## Troubleshooting: Username Skin Not Loading (Rate Limit Fix)

Sometimes, when trying to load a skin by username, you might encounter issues where the skin doesn't appear. This can happen due to:

*   **Rate Limits:** Online services that provide Minecraft skins sometimes impose limits on how many requests can be made in a short period. If many people are using the generator at once, or if you've tried to load skins multiple times in quick succession, you might hit this limit.
*   **Incorrect Username:** Double-check that you've entered your Minecraft username correctly.

### What to do if your username skin doesn't load:

If loading by username doesn't work, don't worry! You can easily use the **"Upload Custom Skin"** function as a workaround.

1.  **Get Your Skin File:**
    *   You can usually download your own Minecraft skin (or any other skin) from websites like [NameMC](https://namemc.com/) or by searching for "Minecraft skin download" on your preferred search engine. Look for a PNG image file of the skin.
2.  **Upload Custom Skin:**
    *   Click the "Upload Custom Skin" button.
    *   Select your downloaded `.png` skin file from your device.
3.  **Important:** Ensure your uploaded skin image has the correct dimensions: either **64x64 pixels** or **64x32 pixels**. The generator will alert you if the dimensions are incorrect.

This method allows you to bypass any potential rate limits or issues with username-based skin fetching and directly use your desired skin.

## Technical Details

The website is built using HTML, CSS, and JavaScript. It utilizes the `<canvas>` element to draw and customize the Minecraft skins and backgrounds. Skin data is fetched from publicly available Minecraft skin services (e.g., Minotar API).

`This is created and owned by Anthroberc. All rights reserved.`
