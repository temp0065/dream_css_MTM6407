# **Welcome to DreamCSS.**
Dream CSS is a lightweight, modern CSS framework designed to provide a clean and responsive foundation for web development. It offers a minimalist approach with customizable components, intuitive styling, and seamless integration with any project. We aim to simplify front-end design while maintaining flexibility and performance.

### CREATED BY: 
- Nathan Templeton 
- Dominic Corriveau 
- Alexander Galstyan
- Matthew Montgomery

<br>
<br>

# **Installation**
You can install DreamCSS in one of the following ways:

### **Option 1: Using npm**
```powershell
npm install dreamcss
```
### **Option 2: Manual Download**
1. Download the DreamCSS framework from GitHub: https://github.com/temp0065/dream_css_MTM6407
2. Include dreamcss.min.css in your project directory.
3. Link it in your HTML: 
```html
<link rel="stylesheet" href="path-to/dreamcss.min.css">
```

<br>
<br>

# **Usage**
To use DreamCSS, simply include it in your project and apply its classes to your HTML elements. Be sure to refer to our frameworks website, for documentation on all of the usable classes.
### **Example: Button Styling**
```html
<button class="dr-btn-success">Complete</button>
```
### **Example: Animations**
DreamCSS also includes built-in animations to enhance user experience. You can use them like this:
```html
<div class="dr-fadeIn">This element fades in!</div>
```

<br>
<br>

# **Customization**
DreamCSS is fully customizable through SCSS variables.
1. Navigate to the scss folder and open the variables.scss file.
2. Modify the variables to fit your design. For example:
```scss
$dream-font: "Lexend", serif;
$font-sizes: (
    "xsm": 0.875rem,
    "sm": 1rem,
    "md": 1.5rem,
    "lg": 2.25rem,
    "xl": 3rem,
    "xxl": 3.75rem
);
```
3. Compile the SCSS using the commands below (in a bash terminal), depending on your preference:
```powershell
sass --watch src/main.scss css/style.css
```
- If you are actively modifying styles
<br>
<br>
```powershell
sass src/main.scss css/style.css
```
- If you just want to compile once
<br>
<br>
4. Your updated styles should now be applied!