# 👻 Ghost Navbar

> Auto-hiding Firefox navbar using `userChrome.css` with smooth transitions and hover reveal.

## ✨ Features

- 🧊 Auto-hide navigation bar
- 🎯 Reveal on hover or focus
- ⚡ Smooth animation
- 🧩 Lightweight (pure CSS)

---

## 📦 Installation

### 1. Enable userChrome support

In Firefox, type the following in the address bar and press Enter:

```
about:config
```

Search for:

```
toolkit.legacyUserProfileCustomizations.stylesheets
```

Set it to `true`.

### 2. Open your Firefox profile folder

In the Firefox address bar, type:

```
about:support
```

Press Enter.

In the **"Profile Folder"** section, click:

👉 **"Open Folder"**

This will open the correct Firefox profile directory.

⚠️ Do not use a random folder — it must be the Firefox profile folder opened by this step.

💡 Example path (Windows):

```
C:\Users\YourUser\AppData\Roaming\Mozilla\Firefox\Profiles\xxxx.default-release\
```

### 3. Create the `chrome` folder

Inside this profile folder, create:

```
chrome/
```

### 4. Add the `userChrome.css` file

Place the file:

```
userChrome.css
```

inside the `chrome` folder.

### 5. Restart Firefox

Close and reopen Firefox to apply the changes.

---

## 📄 License

MIT
