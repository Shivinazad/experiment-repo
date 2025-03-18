## *Project Name - Beautiful Webpage* 



A simple yet elegant webpage created with pure HTML and CSS that features modern design elements, beautiful color gradients, and interactive components.

## 📌 *Preview*

This project creates a visually appealing landing page with:
- Gradient backgrounds
- Animated elements
- Decorative shapes
- Interactive buttons
- Clean, modern typography

## 🎨 *Features*

- **Modern Design**: Clean layout with attention to visual details
- **Color Gradients**: Beautiful blue and pink gradient elements
- **Interactive Elements**: Hover effects and subtle animations
- **Responsive**: Looks good on different screen sizes
- **Pure HTML/CSS**: No external dependencies or libraries

## 💻 *Code*

The webpage is built with simple HTML and CSS:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sample Webpage</title>
    <style>
        /* Enhanced styling with more colors and design elements */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Poppins', 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(120deg, #a1c4fd 0%, #c2e9fb 100%);
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 20px;
        }
        
        .container {
            background-color: rgba(255, 255, 255, 0.9);
            border-radius: 16px;
            padding: 40px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.15);
            max-width: 650px;
            width: 90%;
            position: relative;
            overflow: hidden;
        }
        
        .container::before {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 6px;
            background: linear-gradient(90deg, #ff9a9e 0%, #fad0c4 99%, #fad0c4 100%);
        }
        
        h1 {
            color: #5f27cd;
            margin-bottom: 25px;
            font-weight: 700;
            position: relative;
            display: inline-block;
        }
        
        h1::after {
            content: "";
            position: absolute;
            bottom: -8px;
            left: 0;
            width: 60%;
            height: 3px;
            background-color: #ff9a9e;
        }
        
        p {
            color: #576574;
            line-height: 1.6;
            margin-bottom: 25px;
            font-size: 16px;
        }
        
        .buttons {
            display: flex;
            gap: 15px;
            margin-top: 25px;
            flex-wrap: wrap;
        }
        
        .btn {
            background: linear-gradient(to right, #4facfe 0%, #00f2fe 100%);
            color: white;
            padding: 14px 30px;
            border: none;
            border-radius: 50px;
            cursor: pointer;
            font-size: 16px;
            font-weight: 600;
            letter-spacing: 0.5px;
            transition: all 0.3s ease;
            box-shadow: 0 4px 15px rgba(79, 172, 254, 0.4);
        }
        
        .btn:hover {
            transform: translateY(-3px);
            box-shadow: 0 7px 15px rgba(79, 172, 254, 0.6);
        }
        
        .btn-secondary {
            background: transparent;
            color: #4facfe;
            border: 2px solid #4facfe;
            box-shadow: none;
        }
        
        .btn-secondary:hover {
            background-color: rgba(79, 172, 254, 0.1);
            box-shadow: none;
        }
        
        .icon {
            font-size: 22px;
            margin-right: 8px;
        }
        
        .feature-list {
            margin: 30px 0;
            padding-left: 20px;
        }
        
        .feature-item {
            position: relative;
            padding-left: 28px;
            margin-bottom: 12px;
            color: #576574;
        }
        
        .feature-item::before {
            content: "✓";
            position: absolute;
            left: 0;
            color: #4facfe;
            font-weight: bold;
        }
        
        .footer {
            margin-top: 35px;
            color: #7f8c8d;
            font-size: 14px;
            text-align: center;
            padding-top: 15px;
            border-top: 1px solid #eaeaea;
        }
        
        .highlight {
            background: linear-gradient(120deg, rgba(255, 154, 158, 0.2) 0%, rgba(250, 208, 196, 0.2) 100%);
            padding: 3px 8px;
            border-radius: 4px;
        }
        
        .glow {
            animation: glow 2s infinite alternate;
        }
        
        @keyframes glow {
            from {
                text-shadow: 0 0 5px rgba(79, 172, 254, 0.3);
            }
            to {
                text-shadow: 0 0 15px rgba(79, 172, 254, 0.6);
            }
        }
        
        /* Decorative elements */
        .decoration {
            position: absolute;
            border-radius: 50%;
            opacity: 0.4;
            z-index: -1;
        }
        
        .decoration-1 {
            width: 100px;
            height: 100px;
            background-color: #ff9a9e;
            top: -30px;
            right: -30px;
        }
        
        .decoration-2 {
            width: 60px;
            height: 60px;
            background-color: #4facfe;
            bottom: -20px;
            left: 10%;
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Decorative elements -->
        <div class="decoration decoration-1"></div>
        <div class="decoration decoration-2"></div>
        
        <h1>Welcome to My <span class="highlight glow">Project</span> 🚀</h1>
        <p>This beautiful design was created quickly but looks professional! Check out the features below and get started with this amazing project.</p>
        
        <div class="feature-list">
            <div class="feature-item">Clean and modern design</div>
            <div class="feature-item">Smooth color gradients</div>
            <div class="feature-item">Interactive elements</div>
        </div>
        
        <div class="buttons">
            <button class="btn"><span class="icon">🔥</span>Get Started</button>
            <button class="btn btn-secondary">Learn More</button>
        </div>
        
        <div class="footer">
            Made with ❤️ in just a few minutes • 2025
        </div>
    </div>
</body>
</html>
```
## Screenshot ![image](https://github.com/user-attachments/assets/2b8ed654-91d7-4703-896b-9a4eb09b0087)



## 🚀 Getting Started

1. **Create a new HTML file**: Save the code above as `index.html`
2. **Open in browser**: Double-click the file to open it in your default browser
3. **Customize**: Modify the text, colors, and styles to match your project needs

## 🛠 Technologies Used

HTML5,
CSS3,
JavaScript, 
GitHub Pages (for hosting, if needed)


## 🎨 Design Elements

### Color Scheme
- Background: Blue gradient (`#a1c4fd` to `#c2e9fb`)
- Accent: Pink gradient (`#ff9a9e` to `#fad0c4`)
- Buttons: Blue gradient (`#4facfe` to `#00f2fe`)
- Text: Purple (`#5f27cd`) for headings, Dark gray (`#576574`) for body text

### Special Effects
- **Glow Animation**: Subtle text shadow animation
- **Hover Effects**: Elevation and shadow change on buttons
- **Decorative Elements**: Positioned circular shapes for visual interest
- **Gradient Highlight**: Text highlight with subtle background gradient

## 📱 Responsive Design

The webpage is designed to be responsive and will adjust to different screen sizes:
- Center-aligned content
- Flexible container width
- Wrapping buttons on smaller screens
- Adequate padding for all device sizes

## 🔧 Customization

### Easy to Modify
- Change colors by updating the gradient values
- Modify text content in the HTML
- Adjust sizes and spacing in the CSS
- Add or remove features from the feature list

## Collaborators
Shivin Azad(lead)

Sambhav Sehgal(vice-head)

Dr. Vibhu Sharma(Faculty)

## 📄 License

This project is released under the MIT License.




