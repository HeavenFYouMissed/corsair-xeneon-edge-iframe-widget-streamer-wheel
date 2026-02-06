# � Xeneon Edge Stream Widgets

**Interactive widgets for Corsair Xeneon Edge monitor**

Collection of engaging stream widgets including giveaway wheels and a 3D slot machine! All designed for the Xeneon Edge iframe widget system.

## ✨ Features

### 🎡 Giveaway Wheels
- 🖱️ **Hand Movable** - Drag anywhere on the wheel to spin it like a real fortune wheel
- 🎨 **Three Beautiful Styles** - Choose between Neon, Glassmorphism, or Pastel themes
- ⚡ **Smooth Physics** - Realistic momentum and friction for that perfect spin
- 🎯 **Live Winner Display** - Large number shows the current winner
- 📱 **Touch & Mouse Support** - Works with any input method
- 🔢 **Customizable Segments** - Change number of entries via URL (e.g., `#50` for 50 entries)

### 🎰 3D Slot Machine
- 🎮 **Interactive Lever Pull** - Realistic lever mechanics with pull-and-release action
- 💎 **5-Reel 3D Cylinders** - Stunning CSS 3D transform animations
- 💰 **Betting System** - Multiple bet amounts (10, 25, 50, 100, Max)
- 🎉 **Win Detection** - 3-match (×3), 4-match (×10), 5-match JACKPOT (×25)
- ✨ **Confetti Celebrations** - Particle system with physics for big wins
- 💡 **Flashing Lights** - Top lights flash on wins for extra excitement
- 🎯 **Credits Tracking** - Full credit management with win multipliers

## 🚀 Quick Setup

### Giveaway Wheels

#### Step 1: Choose Your Style

- **wheel-neon.html** - Dark background with vibrant neon colors (pink, orange, yellow, green, blue, purple)
- **wheel-glass.html** - Glassmorphism edition with frosted glass backdrop-filter effect - super premium look!
- **wheel-pastel.html** - Light gradient background with soft pastel colors (bonus edition)

#### Step 2: Copy & Paste

1. Open the HTML file you want to use
2. Select all the code (`Ctrl+A`)
3. Copy it (`Ctrl+C`)
4. Open your Corsair Xeneon Edge monitor widget settings
5. Create a new iframe widget
6. Paste the entire HTML code into the iframe content
7. Save and enjoy!

### 3D Slot Machine

**File:** `slot-machine.html`

1. Open `slot-machine.html`
2. Select all the code (`Ctrl+A`) and copy (`Ctrl+C`)
3. Create a new Xeneon Edge iframe widget
4. Paste the code and save
5. Pull the lever to spin - starts with 1000 credits!

## 🎮 How to Use

### Giveaway Wheels

1. **Spin the wheel**: Click and drag anywhere on the wheel
2. **Watch it spin**: The wheel will spin with realistic physics
3. **See the winner**: The large number at the bottom shows the current winner

#### Change Number of Entries

Add a hash to the URL to set the number of segments:

```
wheel-neon.html#50     → 50 entries (1-50)
wheel-neon.html#100    → 100 entries (1-100)
wheel-neon.html#250    → 250 entries (1-250)
```

Default is 100 entries if no number is specified.

### 3D Slot Machine

1. **Select your bet**: Click bet buttons (10, 25, 50, 100) or Max Bet
   - Active bet is highlighted in green
   - Buttons disable if you can't afford them
2. **Pull the lever**: Click and hold the red lever on the right side
3. **Watch the spin**: 5 reels spin with staggered stopping
4. **Win prizes**:
   - 3 matching symbols → ×3 multiplier + confetti
   - 4 matching symbols → ×10 multiplier + more confetti
   - 5 matching symbols → ×25 JACKPOT + massive confetti
5. **Lights flash** on wins for extra celebration!

## 🎨 Customization

Both files are fully self-contained and easy to customize:

- **Colors**: Edit the `GRADIENT_COLORS` array in the JavaScript section
- **Physics**: Adjust `FRICTION` and `SENSITIVITY` constants
- **Size**: The wheel automatically scales to fit your display

## 📸 Screenshots

*[Screenshots will be added showing both wheel styles in action]*

## 💡 Tips

### Giveaway Wheels
- **Drag fast** for a long spin with lots of momentum
- **Drag slow** for precise control
- Works great for:
  - Stream giveaways
  - Random selections
  - Interactive chat games
  - Viewer engagement

### Slot Machine
- Start with lower bets to make credits last longer
- Max Bet automatically adjusts to your available credits (up to 200)
- Symbols: 🍒 Cherry, 🍋 Lemon, 🍇 Grapes, 🍉 Watermelon, ⭐ Star, 7️⃣ Lucky Seven, 💎 Diamond, 🔔 Bell
- Confetti automatically clears after celebrations
- Perfect for stream overlays and viewer interaction

## 🛠️ Technical Details

### All Widgets
- Pure HTML/CSS/JavaScript - no external dependencies
- Optimized for Xeneon Edge iframe environment
- Touch and pointer event support
- Responsive design scales to any size

### Giveaway Wheels
- Canvas-based rendering for smooth performance
- Custom physics engine with realistic momentum

### Slot Machine
- CSS 3D transforms with `perspective` and `rotateX`
- 12 slots per reel arranged in 3D cylinder
- Canvas-based confetti particle system with gravity
- Cubic-bezier easing for realistic deceleration
- 5-7 full rotations per spin with staggered stopping

## 📝 License

MIT License - Free to use and modify!

---

**Made for streamers who want that extra bit of flair! 🎉**
