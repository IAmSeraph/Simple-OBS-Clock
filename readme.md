# A Simple OBS (browser source) Clock

A simple webpage to embed current date and timestamp in your video/stream.  

&nbsp;  
Original made by [@sam0737](https://gist.github.com/sam0737/a0ee8ca253fc5c84b2aa2ac018f7b8ad).  
This edit mainly introduces locales and adds more font options.  

# Other projects like this

[Simple-OBS-Overlay](https://github.com/IAmSeraph/Simple-OBS-Overlay.git)
[Simple-OBS-Timer](https://github.com/IAmSeraph/Simple-OBS-Timer.git)

# Examples & Usage

  * Vanilla  
    `https://rawcdn.githack.com/IAmSeraph/Simple-OBS-Clock/35c5d6d3b4d0cd97e9bbebfbf1761b3b3ac5266d/index.html`

  * White text  
    `https://rawcdn.githack.com/IAmSeraph/Simple-OBS-Clock/35c5d6d3b4d0cd97e9bbebfbf1761b3b3ac5266d/index.html?style=font: bold 30px monospace; color: white;`

  * Rounded rectangle  
    `https://rawcdn.githack.com/IAmSeraph/Simple-OBS-Clock/35c5d6d3b4d0cd97e9bbebfbf1761b3b3ac5266d/index.html?style=font: bold 30px monospace; color: lightgray; display: inline-block; border-radius: 5px; padding: 2px 5px; background-color: rgba(0, 0, 0, 0.5);`

# Parameters

Use `style` to customize the font, size, color, etc  
Use `bodyStyle` to customize the body of the webpage  
Use `format` to control the output format ([reference](https://momentjs.com/docs/#/displaying/format/))  
Use `locale` to control the language format ([reference](https://www.science.co.il/language/Locale-codes.php))  

&nbsp;  
The default format is '`LTS ll`' which shows the timestamp followed by a short date.  
(if you only want time simply use '`LTS`' for format)  
  
This webpage supports the use of the [Easy Fonts](https://pagecdn.com/lib/easyfonts) library.  
