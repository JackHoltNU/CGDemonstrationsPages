## Structure

```
/
├── index.html          # Main homepage with demo grid
├── css/
│   └── main.css        # Styles for the homepage
├── demos/              # Directory containing all demos
│   ├── example-demo/   # Example demo template
│   │   ├── index.html  # Demo page
│   │   ├── style.css   # Demo styles
│   │   └── script.js   # Demo functionality
│   └── [your-demo]/    # Add new demos here
└── README.md
```

## Adding a New Demo

### Step 1: Create Demo Directory

Create a new folder in the `demos/` directory:

### Step 2: Create Demo Files

Copy the example demo structure or create three files:

1. **index.html** - Your demo page
2. **style.css** - Styling for your demo
3. **script.js** - JavaScript functionality


#### Key Points

- Include a back navigation link: `<a href="../../index.html">Back to Home</a>`
- Keep the demo self-contained within its directory
- Use relative paths for assets
- Match the existing color scheme for consistency (optional)

### Step 3: Add Demo Card to Homepage

Edit `index.html` and add a new demo card to the grid:

```html
<a href="demos/your-demo-name/" class="demo-card">
    <div class="demo-card-content">
        <h2>Your Demo Title</h2>
        <p>Brief description of what your demo demonstrates.</p>
        <div class="demo-tags">
            <span class="tag">HTML</span>
            <span class="tag">CSS</span>
            <span class="tag">JavaScript</span>
        </div>
    </div>
</a>
```

Add this inside the `<main class="demo-grid">` section, before the placeholder card.



