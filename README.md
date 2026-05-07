# 🌊 Atlantico

> A premium dark theme for Visual Studio Code — crafted for long coding sessions, reduced eye strain, and visual clarity across a wide range of languages.

![Version](https://img.shields.io/badge/version-1.0.0-729BB3?style=flat-square)
![VS Code](https://img.shields.io/badge/VS%20Code-^1.70.0-232530?style=flat-square&logo=visual-studio-code&logoColor=729BB3)
![License](https://img.shields.io/badge/license-MIT-BE7878?style=flat-square)

---

## 📸 Screenshots

**JavaScript / TypeScript**

![JavaScript](./screenshots/screenshot-js.png)

**Python**

![Python](./screenshots/screenshot-python.png)

**Rust**

![Rust](./screenshots/screenshot-rust.png)

**CSS / HTML**

![CSS](./screenshots/screenshot-css.png)

**Terminal**

![Terminal](./screenshots/screenshot-terminal.png)

> Place your screenshots inside a `screenshots/` folder at the root of the repository.  
> On Fedora/GNOME, use `gnome-screenshot -f screenshots/screenshot-js.png` or `Print Screen` with VS Code in fullscreen.

---

## ✨ Why Atlantico?

Most dark themes are built for visual impact. Atlantico was built for **endurance**.

Designed for developers with **astigmatism, eye strain, or light sensitivity**, every colour decision in Atlantico was made to reduce fatigue without sacrificing readability. The palette avoids oversaturated neons and harsh whites in favour of soft, ocean-inspired tones that your eyes can rest on for hours.

- **Low visual noise** — muted backgrounds, subtle UI chrome, nothing competing for attention
- **Calibrated contrast** — readable without being aggressive
- **Semantic colour logic** — consistent token roles across all languages, so your brain learns the pattern once
- **Unified experience** — editor and integrated terminal share the same palette, keeping the environment visually coherent

Whether you code for 2 hours or 10, Atlantico is designed to stay comfortable.

---

## 🎨 Palette

### UI

| Role                            | Hex       | Preview                                           |
| ------------------------------- | --------- | ------------------------------------------------- |
| Editor Background               | `#232530` | ![](https://placehold.co/14x14/232530/232530.png) |
| Editor Surface (line highlight) | `#272A34` | ![](https://placehold.co/14x14/272A34/272A34.png) |
| Sidebar                         | `#21232D` | ![](https://placehold.co/14x14/21232D/21232D.png) |
| Activity Bar                    | `#1D1F28` | ![](https://placehold.co/14x14/1D1F28/1D1F28.png) |
| Tab Bar                         | `#1F212B` | ![](https://placehold.co/14x14/1F212B/1F212B.png) |
| Foreground                      | `#CDD6E3` | ![](https://placehold.co/14x14/CDD6E3/CDD6E3.png) |

### Syntax

| Role                               | Hex       | Preview                                           |
| ---------------------------------- | --------- | ------------------------------------------------- |
| Keywords / Tags / Storage          | `#BE7878` | ![](https://placehold.co/14x14/BE7878/BE7878.png) |
| Functions / Decorators / Built-ins | `#729BB3` | ![](https://placehold.co/14x14/729BB3/729BB3.png) |
| Strings / Symbols                  | `#C4A46B` | ![](https://placehold.co/14x14/C4A46B/C4A46B.png) |
| Classes / Types / Interfaces       | `#B8A58A` | ![](https://placehold.co/14x14/B8A58A/B8A58A.png) |
| Numbers / Constants / Parameters   | `#8487D6` | ![](https://placehold.co/14x14/8487D6/8487D6.png) |
| Operators / Punctuation / Regex    | `#8AA7B1` | ![](https://placehold.co/14x14/8AA7B1/8AA7B1.png) |
| Entity Types / CSS Properties      | `#A7B4C2` | ![](https://placehold.co/14x14/A7B4C2/A7B4C2.png) |
| Annotations / Units / Attributes   | `#C29D7C` | ![](https://placehold.co/14x14/C29D7C/C29D7C.png) |
| Inserted / Heredoc / Green accents | `#86A98D` | ![](https://placehold.co/14x14/86A98D/86A98D.png) |
| Comments                           | `#5B6273` | ![](https://placehold.co/14x14/5B6273/5B6273.png) |
| Errors / Invalid                   | `#BE7878` | ![](https://placehold.co/14x14/BE7878/BE7878.png) |

### Terminal

The integrated terminal uses a full ANSI 16-colour palette tuned to match the editor — muted, warm tones for normal colours and slightly brighter variants for the bold/bright layer.

| ANSI    | Normal                                                      | Hex | Bright                                                      | Hex |
| ------- | ----------------------------------------------------------- | --- | ----------------------------------------------------------- | --- |
| Black   | ![](https://placehold.co/14x14/2A2D37/2A2D37.png) `#2A2D37` |     | ![](https://placehold.co/14x14/5B6273/5B6273.png) `#5B6273` |
| Red     | ![](https://placehold.co/14x14/BE7878/BE7878.png) `#BE7878` |     | ![](https://placehold.co/14x14/C77D7D/C77D7D.png) `#C77D7D` |
| Green   | ![](https://placehold.co/14x14/769986/769986.png) `#769986` |     | ![](https://placehold.co/14x14/86A995/86A995.png) `#86A995` |
| Yellow  | ![](https://placehold.co/14x14/A98D63/A98D63.png) `#A98D63` |     | ![](https://placehold.co/14x14/B89B6A/B89B6A.png) `#B89B6A` |
| Blue    | ![](https://placehold.co/14x14/729BB3/729BB3.png) `#729BB3` |     | ![](https://placehold.co/14x14/84A9BF/84A9BF.png) `#84A9BF` |
| Magenta | ![](https://placehold.co/14x14/9A84C7/9A84C7.png) `#9A84C7` |     | ![](https://placehold.co/14x14/A695D6/A695D6.png) `#A695D6` |
| Cyan    | ![](https://placehold.co/14x14/7AA2B8/7AA2B8.png) `#7AA2B8` |     | ![](https://placehold.co/14x14/8EB8C7/8EB8C7.png) `#8EB8C7` |
| White   | ![](https://placehold.co/14x14/CDD6E3/CDD6E3.png) `#CDD6E3` |     | ![](https://placehold.co/14x14/E6EDF7/E6EDF7.png) `#E6EDF7` |

---

## 🌐 Supported Languages

Atlantico includes fine-tuned token rules for a wide range of languages:

| Category          | Languages                                               |
| ----------------- | ------------------------------------------------------- |
| **Web**           | JavaScript, TypeScript, JSX, TSX, HTML, CSS, SCSS, Less |
| **Systems**       | Rust, C, C++, Go                                        |
| **JVM**           | Java, Kotlin                                            |
| **Scripting**     | Python, Ruby, PHP, Shell / Bash                         |
| **Data & Config** | JSON, YAML, TOML, XML, GraphQL, SQL                     |
| **Tooling**       | Dockerfile, Markdown, Git diff                          |

---

## 📦 Installation

### Via VS Code Marketplace _(coming soon)_

1. Open VS Code
2. Go to **Extensions** (`Ctrl+Shift+X`)
3. Search for **Atlantico**
4. Click **Install**
5. Open **File → Preferences → Color Theme** and select **Atlantico**

### Manual Installation

```bash
# Clone the repository
git clone https://github.com/gvenancio/atlantico.git ~/.vscode/extensions/atlantico

# Restart VS Code, then open:
# File → Preferences → Color Theme → Atlantico
```

---

## 💡 Recommended Settings

For the best experience alongside Atlantico:

```json
{
  "editor.fontFamily": "'JetBrains Mono', 'Fira Code', monospace",
  "editor.fontSize": 14,
  "editor.lineHeight": 1.7,
  "editor.fontLigatures": true,
  "editor.cursorBlinking": "smooth",
  "editor.renderLineHighlight": "line",
  "workbench.colorTheme": "Atlantico"
}
```

A monospace font with ligatures pairs especially well with Atlantico's operator and punctuation colouring.

---

## 🤝 Contributing

If you find a language or edge case where the highlighting feels off, contributions are welcome.

1. Fork the repository
2. Create a branch: `git checkout -b fix/python-decorator`
3. Make your changes and commit: `git commit -m 'fix: improve Python decorator contrast'`
4. Push and open a Pull Request

Please include a before/after screenshot when changing token colours.

---

## 📄 License

MIT © [Gonçalo Venâncio](https://github.com/gvenancio)

---

<div align="center">
  <sub>Built with 🌊 for developers who live in the deep end.</sub>
</div>
