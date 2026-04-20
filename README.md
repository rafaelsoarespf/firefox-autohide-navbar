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

---

## 🇧🇷 Português

### 👻 Barra de navegação fantasma

> Ocultar automaticamente a barra de navegação do Firefox usando `userChrome.css` com transições suaves e revelação instantânea.

## ✨ Recursos

- 🧊 Ocultar automaticamente a barra de navegação
- 🎯 Revelar ao passar o mouse ou focar
- ⚡ Animação suave
- 🧩 Leve (CSS puro)

---

## 📦 Instalação

### 1. Habilite o suporte do userChrome

No Firefox, digite o seguinte na barra de endereço e pressione Enter:

```
about:config
```

Procure por:
```
toolkit.legacyUserProfileCustomizations.stylesheets
```

Altere o valor para `true`.

### 2. Abra a pasta de perfil do Firefox

Na barra de endereço do Firefox, digite:

```
about:support
```

Pressione Enter.

Na seção **"Pasta de perfil"**, clique em:

👉 **"Abrir pasta"**

Isso abrirá o diretório correto do perfil do Firefox.

⚠️ Não use uma pasta aleatória — deve ser a pasta do perfil do Firefox aberta nesta etapa.

💡 Caminho de exemplo (Windows):

```
C:\Users\SeuUsuário\AppData\Roaming\Mozilla\Firefox\Profiles\xxxx.default-release\
```

### 3. Crie a pasta `chrome`

Dentro desta pasta de perfil, crie:

```
chrome/
```

### 4. Adicione o arquivo `userChrome.css`

Coloque o arquivo:

```
userChrome.css
```

dentro da pasta `chrome`.

### 5. Reinicie o Firefox

Feche e reabra o Firefox para aplicar as alterações.

---

## 📄 Licença

MIT
