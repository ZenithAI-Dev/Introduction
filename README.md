# ZenithAI OS

**ZenithAI OS** is a futuristic web-based operating system interface built for crypto-native users. Inspired by macOS and terminal environments, ZenithAI OS combines the power of AI, blockchain, and personalized automation into a seamless, interactive experience.

---

## Features

### Terminal Interface
An interactive, stylized command-line terminal:
- `/help`: Displays available commands
- `/connect_wallet`: Securely connects to Phantom Wallet (Solana)
- `/strategy_maker`: Launches AI-powered trading strategy generator
- `/clear`: Clears the terminal
- `/ca`: Outputs specific contract address/code

### Strategy Maker (AI-Powered)
ZenithAI OS includes a multi-step command (`/strategy_maker`) to build personalized crypto trading strategies. Just provide:
1. Your Balance
2. Monthly Income
3. Duration of Trading Plan  
➡️ An AI agent will then generate a detailed, private strategy tailored to your input.

### Phantom Wallet Integration
Securely connect and manage your **Solana-based assets** directly from the interface.

### Desktop-like UX
- Draggable, resizable windows (Terminal & Info Popup)
- Live Battery Indicator (macOS style)
- Real-time Clock
- Interactive Dock with app shortcuts

### Info Center
The Information window provides:
- Your Public IP Address (via `ipify`)
- Wallet connection status
- Overview of ZenithAI's utility:
  - Secure Wallet Interaction
  - AI-based Automation
  - Deep Learning-powered Insights

### Dock Shortcuts
Integrated access to:
- Terminal
- Info Center
- [X (Twitter)](https://x.com/aizenithere?)
- [Telegram Channel](https://t.me/ZenithAiAnn)

---




## 🛠 Installation & Usage

1. **Clone the repository**
   ```bash
   git clone https://github.com/ZenithAI-OS/introduction.git
   cd ZenithAI-OS
   ```

2. **Open in your browser**
   Just open `index.html` with your preferred browser (Chrome recommended).

3. **Optional: Add backend endpoint `/ask`**
   - POST endpoint expected by `/strategy_maker` to process AI prompts.
   - Payload: `application/x-www-form-urlencoded`
     ```
     message=Your strategy prompt here
     ```
   - Response format:
     ```json
     {
       "response": "AI generated trading strategy..."
     }
     ```

---

## 🧪 Commands Summary

| Command           | Description                                         |
|------------------|-----------------------------------------------------|
| `/help`          | Display available commands                         |
| `/connect_wallet`| Connect Phantom Wallet                             |
| `/strategy_maker`| Launch AI strategy generator                        |
| `/ca`            | Outputs contract address or code                    |
| `/clear`         | Clear terminal content                              |

---

## 📜 License

This project is licensed under the MIT License.  
Feel free to fork, enhance, and contribute!

---

> Developed by ZenithAI Dev — empowering crypto innovation.
