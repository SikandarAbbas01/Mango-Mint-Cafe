# 🥭 Mango Mint Café — Multimodal Adaptive UI

Mango Mint Café is an interactive, responsive café ordering website developed using HTML, CSS, and vanilla JavaScript. It demonstrates a **Multimodal Adaptive User Interface (UI)** that adapts to different interaction methods, including mouse, touch, keyboard, and voice commands.

The project combines a simulated café ordering system with accessibility features, customizable themes, gesture-based controls, and real-time interaction monitoring to provide an inclusive and user-friendly experience.

## ✨ Features

### 🧋 1. Interactive Café Menu
- Browse drinks, food items, and sweets.
- Search for products by name.
- Filter products by category.
- View item descriptions, prices, and calorie information.
- Add items to the cart.
- Mark products as favourites.

### 🛒 2. Shopping Cart and Order Management
- Add, increase, decrease, and remove items.
- Calculate subtotal, discount, tip, and final total automatically.
- Apply the `MANGO10` promotional code for a 10% discount.
- Select tips of 0%, 5%, 10%, or 15%.
- Clear the current order.
- Place simulated orders and generate order numbers.
- View recent orders and reorder previously purchased items.

### 🎙️ 3. Voice-Based Interaction
The website supports voice commands through the browser's Web Speech API when available.

Examples of supported commands include:

- `Add two mango latte`
- `Remove donut`
- `Show drinks`
- `Search brownie`
- `Apply promo`
- `Tip ten`
- `Ocean theme`
- `Bigger text`
- `Read order`
- `Place order`
- `Clear`
- `Stop listening`

Voice functionality depends on browser compatibility and microphone permissions.

### 🖱️ 4. Mouse-Based Interaction
Mouse users can interact with the interface through:
- Hover effects on menu cards.
- Double-clicking products to add them to favourites.
- Right-clicking products to view additional details.
- Interactive buttons and controls.
- Visual feedback when interacting with elements.

### 📱 5. Touch and Gesture-Based Interaction
The interface supports touch gestures on compatible devices:

- Swipe a menu card right to add an item to the cart.
- Double-tap a product to mark it as a favourite.
- Long-press a product to view its details.
- Swipe an order item left to remove it.
- Pinch to adjust the text size.

Touch mode also provides larger controls for easier interaction.

### ⌨️ 6. Keyboard Accessibility

The website supports keyboard navigation and shortcuts.

| Shortcut | Function |
|---|---|
| `/` | Focus the menu search field |
| `Tab` | Navigate between interactive elements |
| `Enter` | Activate the focused control |
| `Alt + M` | Cycle through input mode settings |
| `Alt + V` | Toggle voice interaction |
| `Alt + T` | Cycle through themes |
| `+` or `=` | Increase text size |
| `-` | Decrease text size |
| `?` | Open the help and shortcuts dialog |

Visible focus indicators help users identify the currently focused element.

### 🎨 7. Adaptive Themes and Personalization

Users can customize the interface according to their preferences.

Available themes:
- Aurora
- Sunset
- Ocean
- High Contrast
- Automatic Theme

Additional personalization options include:
- Adjustable text size from 85% to 150%.
- Reduced motion and visual effects.
- Optional sound feedback.
- Spoken replies.
- Automatic, mouse, touch, and keyboard input modes.

### 📊 8. Live Input Monitor

The live input monitor displays interaction statistics for:

- Mouse
- Touch
- Keyboard
- Voice
- Gestures

It also maintains a recent event log, allowing users to observe how different interaction methods are used during a session.

### 💾 9. Local Data Persistence

The application uses browser `localStorage` to preserve selected settings, cart contents, favourites, and recent order history.

Saved information remains available after refreshing the page in the same browser profile, provided local browser data has not been cleared.

The **Reset Everything** option restores the demo to its initial state.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Page structure and content |
| CSS3 | Responsive layout, themes, animations, and visual styling |
| JavaScript | Application logic and interactive functionality |
| Web Speech API | Voice command recognition and spoken responses |
| Web Audio API | Sound feedback |
| Canvas API | Background effects and order confirmation animations |
| LocalStorage | Saving preferences and demo order data |
| Pointer Events API | Mouse, touch, and gesture interactions |
| Vibration API | Haptic feedback on supported devices |

The project uses vanilla JavaScript without external frameworks or package dependencies.

## 🚀 Installation and Setup

### Option 1: Run Locally

1. Download or clone the repository.
2. Locate the HTML file.
3. Open it in a modern web browser.
4. Explore the menu and test the available features.

### Option 2: Run Through a Local Server

If Python is installed, open a terminal in the project directory and execute:

```bash
python -m http.server 8000
```

Open the following address in your browser:

```text
http://localhost:8000
```

If the HTML file is not named `index.html`, open its filename through the local server.

## 📁 Project Structure

The project is contained in a single HTML file.

```text
Mango-Mint-Cafe/
│
├── adaptiveCafe.html
└── README.md
```

The HTML file contains the page structure, CSS styling, and JavaScript functionality.

## 🧪 How to Test the Application

1
