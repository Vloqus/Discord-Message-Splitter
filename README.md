# Discord Message Splitter - Made by Jan

A sleek, fully customizable single-page web app that splits a long Discord message (over 2000 characters) into smaller parts. Each part can be easily copied by clicking, with smooth tweened animations and a stylish interface inspired by modern Microsoft design.

![Screenshot](https://cdn.discordapp.com/attachments/1344383991205331085/1345221740770623580/Htcsc8H.png?ex=67c3c2e0&is=67c27160&hm=f754c6ebb3cce342435c6ba689df44501f02e7873090be7b5365a659eca6b14e&)

## Features

- **Three Themes:**  
  - **Dark:** A moody, gradient black background.  
  - **Light:** A clean, white/light gray design.  
  - **Fun:** A vibrant, multi-color gradient with a blurred glass effect.

- **Responsive Layout:**  
  - The main input area (textarea) is centered and styled in gray.
  - The parts container expands and becomes scrollable as more parts are generated.

- **Interactive Buttons:**  
  - Modern, rectangular, blackish buttons with rounded corners.
  - A theme toggle button (moon emoji 🌙) to cycle through the available themes.

- **Smooth Animations:**  
  - Split parts fade in with a tweened effect.
  - Clicking on a part copies its content and shows a floating "Copied!" notification with a blur effect.
  - Animated, rainbow-gradient "Jan" in the footer links to your GitHub.

- **Easy to Use:**  
  - Simply paste your long message into the input box, click "Split Message", and scroll to view & copy each split part.

## Usage

1. **Download or Clone the Repository:**  
   Save the `index.html` file to your computer.

2. **Open the App:**  
   Open `index.html` in any modern web browser.
OR
  Use it online by using 

3. **Split a Message:**  
   - Paste a long message (over 2000 characters) into the textarea.
   - Click the **"Split Message"** button.
   - The message will be split into parts and displayed in a scrollable container below.
   - Click any part to copy its full text (the part will briefly blur and a "Copied!" notification will appear).

4. **Switch Themes:**  
   - Click the moon emoji button (🌙) at the top left to cycle through Dark, Light, and Fun themes.

## Customization

- **Themes:**  
  Modify the CSS variables in the `<style>` section of `index.html` to change colors, fonts, or gradients to your liking.

- **Chunk Size:**  
  By default, messages are split into 2000-character chunks. You can change this value by modifying the `chunkSize` variable in the JavaScript section.

- **Animations:**  
  The staggered fade-in and tween effects are defined in the CSS. You can adjust timing by editing the corresponding `transition` and `animation` properties.

## Contributing

Feel free to fork the repository and make your own modifications. Pull requests are welcome!

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Author

Made by [Jan](https://github.com/Vloqus)  
Enjoy and have fun splitting your messages!
