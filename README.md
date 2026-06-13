# ⚡ Taiki — Discord Quest Automator (Vencord Plugin + Console)


> **Auto‑complete all Discord quests** (videos, games, streams, activities, achievements) with a sleek glass‑morphic UI.  
> *Requires Vencord + a custom plugin, then one console command.*

---

## 📦 Installation

### 1. Install Vencord
- Download and install [Vencord](https://vencord.dev/) for Discord Desktop.

### 2. Add the Taiki plugin
- Download the custom plugin file (`taikiPlugin.js`) from this repository.

### 3. Run Taiki
- Open Discord Desktop.  
- Press **`Ctrl + Shift + I`** to open DevTools.  
- Go to the **Console** tab.  
- **Paste** the following command and press `Enter`:

💬 **Community** – Join our [Discord Server](https://discord.gg/xQV76wxy8F) for support and updates.

```js
(async () => { const s = document.createElement('script'); s.src = 'https://raw.githubusercontent.com/0e644/Taiki/main/taiki.user.js'; document.head.appendChild(s); })();
