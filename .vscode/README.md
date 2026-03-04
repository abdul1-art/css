# 🚀 VSCode Auto-Complete & Snippets Guide

Selamat! VSCode Anda sekarang sudah dikonfigurasi dengan custom snippets dan keyboard shortcuts otomatis. Berikut panduan lengkapnya:

---

## 📋 CSS Snippets (Ketik dan Tekan Tab)

| Prefix  | Description              |
| ------- | ------------------------ |
| `fx`    | Flexbox Container        |
| `fxc`   | Flexbox Center           |
| `fxcol` | Flexbox Column           |
| `fxb`   | Flexbox Space Between    |
| `fxw`   | Flexbox Wrap             |
| `gd`    | Grid Container           |
| `pac`   | Position Absolute Center |
| `pa`    | Absolute Positioning     |
| `mqm`   | Media Query Mobile       |
| `mqt`   | Media Query Tablet       |
| `kf`    | Keyframes Animation      |
| `tr`    | Transition               |
| `bh`    | Button Hover             |
| `bm`    | Box Model Reset          |
| `cont`  | Container                |
| `tt`    | Text Truncate            |
| `gb`    | Gradient Background      |
| `bs`    | Box Shadow               |
| `br`    | Border Radius            |
| `ff`    | Font Family              |
| `fi`    | Font Import              |
| `zi`    | Z-Index                  |
| `oh`    | Overflow Hidden          |
| `ofc`   | Object Fit Cover         |
| `cv`    | CSS Variable             |
| `calc`  | Calc Function            |

### Contoh Penggunaan:

1. Ketik `fxc` di file CSS
2. Tekan `Tab`
3. 自动 (Otomatis) menghasilkan:

```
css
display: flex;
justify-content: center;
align-items: center;
```

---

## 📋 HTML Snippets (Ketik dan Tekan Tab)

| Prefix    | Description        |
| --------- | ------------------ | ---------- |
| `html`    | HTML5 Boilerplate  |
| `lcss`    | Link CSS           |
| `meta`    | Meta Tags          |
| `nav`     | Navigation Bar     |
| `header`  | Header Element     |
| `footer`  | Footer Element     |
| `section` | Section            |
| `card`    | Card Element       |
| `btn`     | Button             |
| `ul`      | Unordered List     |
| `ol`      | Ordered List       |
| `form`    | Form               |
| `input`   | Input              |
| `select`  | Select Dropdown    |
| `gfont`   | Googlefa`          | Font Fonts |
| ` Awesome |
| `bscss`   | Bootstrap CSS      |
| `bsjs`    | Bootstrap JS       |
| `bemc`    | BEM Card Structure |

### Contoh Penggunaan:

1. Ketik `nav` di file HTML
2. Tekan `Tab`
3. 自动 (Otomatis) menghasilkan:

```
html
<nav class="navbar">
    <div class="logo">
    </div>
    <ul class="nav-links">
        <li><a href="#">Link</a></li>
    </ul>
</nav>
```

---

## ⌨️ Keyboard Shortcuts Penting

### 🔥 Shortcuts yang Sering Dipakai:

| Shortcut           | Action           |
| ------------------ | ---------------- |
| `Ctrl + D`         | Duplicate baris  |
| `Alt + ↑ / ↓`      | Pindah baris     |
| `Ctrl + /`         | Comment baris    |
| `Ctrl + Shift + /` | Block comment    |
| `Ctrl + Shift + K` | Hapus baris      |
| `Ctrl + P`         | Quick open file  |
| `Ctrl + Shift + P` | Command Palette  |
| `Ctrl + B`         | Toggle sidebar   |
| `Ctrl + J`         | Toggle panel     |
| `Alt + L + O`      | Open Live Server |
| `Shift + Alt + F`  | Format document  |

### 📝 Multi-Cursor:

| Shortcut           | Action                 |
| ------------------ | ---------------------- |
| `Ctrl + Alt + ↑`   | Tambah cursor di atas  |
| `Ctrl + Alt + ↓`   | Tambah cursor di bawah |
| `Ctrl + Shift + L` | Select semua sama      |

### 🔤 Text Transformation:

| Shortcut           | Action    |
| ------------------ | --------- |
| `Ctrl + Shift + U` | UPPERCASE |
| `Ctrl + Shift + L` | lowercase |

---

## ⚡ Emmet (Built-in)

VSCode sudah support Emmet. Coba ini:

### HTML:

```
html
<!-- Ketik ini: -->
div.container>ul>li*3>a

<!-- Hasil: -->
<div class="container">
    <ul>
        <li><a href=""></a></li>
        <li><a href=""></a></li>
        <li><a href=""></a></li>
    </ul>
</div>
```

### CSS:

```
css
/* Ketik ini: */
pos:a

/* Hasil: */
position: absolute;
```

---

## 📦 Extension yang Direkomendasikan

Buka VSCode dan install extension ini:

1. **ESLint** - Linter JavaScript
2. **Prettier** - Code formatter
3. **Auto Rename Tag** - Rename tag otomatis
4. **Auto Complete Tag** - Lengkapin tag
5. **Path Intellisense** - Auto path
6. **CSS Peek** - Preview CSS
7. **Live Server** - Server lokal
8. **Emmet Live** - Emmet syntax

---

## 🎯 Tips Produktivitas

1. **Snippet**: Ketik prefix → Tekan `Tab`
2. **Emmet**: Ketik abbreviation → Tekan `Tab`
3. **Multi-cursor**: `Ctrl + Alt + ↓`
4. **Quick replace**: `Ctrl + H`
5. **Format**: `Shift + Alt + F`

---

## 🔄 Cara Aktifkan

1. **Buka folder ini di VSCode**
2. **VSCode akan auto-detect** konfigurasi di `.vscode/`
3. **Mulai coding!** Snippets dan shortcuts langsung работает

---

Happy Coding! 🎉
