# Discord Message Splitter - Made by Jan

A sleek, fully customizable single-page web app that splits a long Discord message (over 2000 characters) into smaller parts. Each part can be easily copied with a click, featuring smooth tweened animations, a responsive layout, and a modern interface inspired by Microsoft design principles.

The app now includes an advanced settings menu that lets you adjust everything from the chunk size and border thickness to the font and animation speed—all of which automatically adapt to your chosen theme.

![Screenshot](https://cdn.discordapp.com/attachments/1344383991205331085/1345221740770623580/Htcsc8H.png?ex=67c3c2e0&is=67c27160&hm=f754c6ebb3cce342435c6ba689df44501f02e7873090be7b5365a659eca6b14e&)

## Features

- **Three Themes:**  
  - **Dark:** A moody, black background with subtle gradients.  
  - **Light:** A clean, white/light gray design.  
  - **Fun:** A vibrant, colorful theme with dynamic gradients.

- **Responsive & Scrollable Layout:**  
  - The main input area (textarea) is centered and styled in gray.
  - The parts container grows in height with your content—scrolling naturally if needed.

- **Advanced Settings Menu:**  
  - Adjust the **chunk size** (number of characters per split).
  - Customize **border thickness**, **border radius**, **font size**, and **font family**.
  - Toggle and control **animations** and **notifications** (including duration).
  - Set a **maximum number of parts** to display (or leave unlimited).
  - Enter **custom CSS** for further personalization.
  - A **Reset to Default** option is available to quickly revert all settings.

- **Interactive Buttons:**  
  - Modern, rectangular, blackish buttons that change colors based on the active theme.
  - A theme toggle button (moon emoji 🌙) cycles through Dark, Light, and Fun themes.
  - A gear icon button opens the settings menu.

- **Smooth Animations & Effects:**  
  - Split parts fade and slide in with a staggered tweened effect.
  - Clicking on a part copies its full text and shows a floating "Copied!" notification with a blur effect.
  - The footer features an animated, rainbow-gradient "Jan" that links to your GitHub.

## Usage

1. **Download or Clone the Repository:**  
   Save the `index.html` file to your computer.

2. **Open the App:**  
   Open `index.html` in any modern web browser.

   **OR**

   Use it online at: [https://vloqus.github.io/Discord-Message-Splitter/](https://vloqus.github.io/Discord-Message-Splitter/)

3. **Split a Message:**  
   - Paste a long message (over 2000 characters) into the input textarea.
   - Click the **"Split Message"** button.
   - The message will be split into parts and displayed in a scrollable container.
   - Click on any part to copy its full text (the part will briefly blur and a "Copied!" notification will appear).

4. **Customize Settings:**  
   - Click the gear icon (⚙️) at the top right to open the settings menu.
   - Adjust various options such as chunk size, border settings, font properties, animation speed, and more.
   - Click **"Save Settings"** to apply changes or **"Reset to Default"** to revert.
   - All settings persist between sessions via localStorage.

5. **Switch Themes:**  
   - Click the moon emoji button (🌙) at the top left to cycle through the Dark, Light, and Fun themes.
   - The interface, including button colors and the settings menu, will automatically adapt to the selected theme.

## Customization

- **Themes:**  
  Modify the CSS variables in the `<style>` section to further tailor colors, fonts, or gradients.

- **Settings Menu:**  
  Use the built-in settings menu to change the chunk size, border styles, font, animation, and more. Advanced users can also add custom CSS for additional tweaks.

## Contributing

Feel free to fork the repository and enhance the project. Pull requests are welcome!

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Author

Made by [Jan](https://github.com/Vloqus)

Enjoy and have fun splitting your messages!
