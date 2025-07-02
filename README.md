# Pick 10

A web-based puzzle game where players select groups of numbers that sum to exactly 10. This game was entirely coded by AI.

## 🎮 How to Play

1. **Objective**: Select groups of numbers that add up to exactly 10
2. **Selection**: Click and drag (or touch and drag on mobile) to create a rectangle around numbers
3. **Validation**: If the selected numbers sum to 10, they turn gray and become inactive
4. **Goal**: Clear the entire grid by selecting all valid combinations
5. **Undo**: Use the "Undo" button or press Backspace to reverse your last move

## 🎯 Game Features

- **4x4 Grid**: Classic puzzle format with 16 numbers
- **Touch Support**: Fully playable on mobile devices
- **Visual Feedback**: Real-time rectangle drawing while selecting
- **Undo System**: Reverse moves with button or keyboard shortcut
- **Custom Puzzles**: Create your own puzzles using the builder
- **URL Sharing**: Share specific puzzles via URL parameters

## 🛠️ Builder Tool

The game includes a built-in puzzle builder (`builder.html`) that allows you to:

- **Create Custom Grids**: Input your own 4x4 number arrangements
- **Quick Input**: Click/tap cells to increment numbers (1-9, wraps to 1)
- **Generate Links**: Create shareable URLs for your custom puzzles
- **Clear Function**: Reset the entire grid with one click

### Using the Builder

1. Navigate to `builder.html`
2. Click on any cell to set numbers (1-9)
3. Fill the entire 4x4 grid
4. Click "Create Game" to generate a shareable link
5. Copy the link to share your custom puzzle

## 🔗 URL Parameters

The game supports a `q` parameter for custom puzzles:

```
index.html?q=5418282326235171
```

The `q` parameter should contain exactly 16 digits representing the grid from left to right, top to bottom.

## 🎨 Technical Details

- **Pure HTML/CSS/JavaScript**: No external dependencies
- **Responsive Design**: Works on desktop and mobile
- **Touch Events**: Native touch support for mobile devices
- **Keyboard Support**: Backspace key for undo functionality
- **Visual Polish**: Smooth animations and hover effects

## 🚀 Getting Started

1. Open `index.html` in any modern web browser
2. Start playing with the default puzzle
3. Use the "Builder" link in the bottom right to create custom puzzles
4. Share puzzle links with friends

## 📱 Browser Compatibility

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🎯 Game Strategy Tips

- Look for obvious pairs that sum to 10 (e.g., 1+9, 2+8, 3+7, 4+6, 5+5)
- Plan your selections to avoid blocking other combinations
- Use the undo feature to experiment with different approaches
- Some puzzles may have multiple valid solutions

## 🤖 AI-Generated

This entire game was coded by AI, demonstrating the capabilities of modern AI systems in creating functional, user-friendly web applications with:

- Clean, maintainable code structure
- Intuitive user interface design
- Cross-platform compatibility
- Modern web development practices

---

*Enjoy playing Pick 10! Challenge yourself with the default puzzle or create your own custom challenges.*
