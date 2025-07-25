# Pick 10

A web-based puzzle game where players select groups of numbers that sum to exactly 10. This game was (mostly) coded by AI.

[Live demo](https://jminjie.github.io/pick10/)

## 🎮 How to Play

1. **Objective**: Select groups of numbers that add up to exactly 10
2. **Selection**: Click and drag (or touch and drag on mobile) to create a rectangle around numbers
3. **Validation**: If the selected numbers sum to 10, they turn gray and become inactive
4. **Goal**: Clear the entire grid by selecting valid combinations
5. **Undo**: Use the "Undo" button or press Backspace to reverse your last move

## 🎯 Game Features

- **Touch Support**: Fully playable on mobile devices
- **Visual Feedback**: Real-time rectangle drawing while selecting
- **Undo System**: Reverse moves with button or keyboard shortcut
- **Custom Puzzles**: Create your own puzzles using the builder
- **URL Sharing**: Share specific puzzles via URL parameters

## 🛠️ Builder Tool

The game includes a built-in puzzle builder (`builder.html`) that allows you to:

- **Create Custom Grids**: Input your own number arrangements
- **Mobile Input**: Tap cells on mobile to increment numbers (1-9, wraps to 1)
- **Generate Links**: Create shareable URLs for your custom puzzles
- **Clear Function**: Reset the entire grid with one click

## 🔗 URL Parameters

The game supports a `q`, `r` and `c` parameters for custom puzzles:

```
index.html?q=5418282326235171&r=4&c=4
```

The `q` parameter represents the grid from left to right, top to bottom.
If `r` and `c` are not provided, the standard 4x4 size is assumed.

## 🎨 Technical Details

- **Pure HTML/CSS/JavaScript**: No external dependencies
- **Responsive Design**: Works on desktop and mobile
- **Touch Events**: Native touch support for mobile devices
- **Keyboard Support**: Backspace key for undo functionality

## 🚀 Getting Started

1. Open `index.html` in any modern web browser
2. Start playing with the default puzzle
3. Use the "Builder" link in the bottom right to create custom puzzles
4. Share puzzle links with friends

## 📱 Browser Compatibility

- Chrome
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
