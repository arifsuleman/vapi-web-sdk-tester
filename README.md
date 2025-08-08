# Vapi Web SDK Tester

This is a front-end Vapi tester that lets you try out the [Vapi Web SDK](https://docs.vapi.ai) without any backend.

## 🚀 Features

- Load Vapi Web SDK via CDN (no build tools required)
- Custom Start/Stop buttons to simulate voice calls
- Progress bar animation
- Dark theme interface

## 🔧 Setup

1. Clone or download this repository.
2. Open `index.html` in your browser.
3. Replace the following in the `<script>` tag of `index.html`:
   - `apiKey`: Your **_public API key_**
   - `assistant`: Your **_assistant ID_**

## 📁 Files

- `index.html` – Main web interface.
- `style.css` – Custom styles for buttons, notes, and layout.
- `README.md` – Project overview and instructions.

## 🧪 How It Works

The Vapi SDK script is loaded via CDN:

```html
<script src="https://cdn.jsdelivr.net/gh/VapiAI/html-script-tag@latest/dist/assets/index.js"></script>
```

Once loaded, `window.vapiSDK.run()` is initialized with your API key and assistant ID. Start/Stop buttons trigger the embedded `.vapi-btn` to simulate voice interaction.

## 📸 Preview

![preview](https://vapi.ai/static/vapi-preview.png) <!-- Replace with real preview if needed -->

## 📄 License

MIT