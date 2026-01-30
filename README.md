# Chrome_X_Hackatime_Extension 🚀

A Chrome extension to track GitHub activity using **Hackatime**  
(compatible with WakaTime / Hackatime dashboards)

---

## 📌 Description

**Chrome_X_Hackatime_Extension** is a Chrome browser extension that tracks your GitHub activity and sends heartbeats to **Hackatime**.  
This allows you to see your GitHub coding activity alongside your editor activity in Hackatime.

The extension detects:
- Programming language (e.g. Markdown, JavaScript)
- Editor (Chrome)
- Operating system
- Project name

---

## ✨ Features

- ⏱️ Automatic heartbeat tracking for GitHub
- 🧠 Language detection based on file type
- 🖥️ Editor & OS identification
- ⚙️ Settings page with status indicator
- 🟢🟥 Active / Inactive status display
- 🔒 No unnecessary data storage

---

## 🧪 Demonstration

### 1️⃣ Open a GitHub Repository
When you open a GitHub file (e.g. `README.md`, `.js`, `.py`), the extension automatically detects the file.

### 2️⃣ Heartbeat is sent
A heartbeat is sent to Hackatime with the following data:

```json
{
  "project": "chrome_github_x_hackatime",
  "language": "Markdown",
  "editor": "Chrome",
  "operating_system": "Windows",
  "category": "coding"
}
