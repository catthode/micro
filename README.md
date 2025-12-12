# Catthode for Micro

> **From CRT to OLED.** Bringing warmth back to a world of cold themes. 

Catthode is a high-contrast, retro-futuristic theme designed for prolonged coding sessions. It blends the crushed blacks of modern OLED displays with the comforting, warm glow of analog tungsten filaments.

## 🎨 Color Palette

### Surface
| Color | Hex | Role |
| :--- | :--- | :--- |
| **Base** | `#000000` | Editor background, pure void |
| **Sidebar** | `#141414` | Sidebars, panels, widgets |
| **Selection** | `#2d2d2d` | Text selection, hover states, buttons |
| **Border** | `#636363` | Borders, subtle dividers |

### Phosphor
| Color | Hex | Role |
| :--- | :--- | :--- |
| **Text** | `#ffffff` | Standard text |
| **Variable** | `#e8e8e8` | Variables, identifiers |
| **Comment** | `#b3b3b3` | Comments, docstrings |
| **Ignored** | `#757575` | Ignored files, disabled elements |

### Glow
| Color | Hex | Role |
| :--- | :--- | :--- |
| **Wheat** | `#fae2c8` | Types, classes, bright glow |
| **Tan** | `#d9b98c` | Secondary glow |
| **Gold** | `#ffb86c` | Keywords, storage, headers |
| **Amber** | `#ff9e3b` | Functions, accents, active states |
| **Clay** | `#f08d49` | Operators, punctuation |

### Accents
| Color | Hex | Role |
| :--- | :--- | :--- |
| **Red** | `#ff6b6b` | Errors, deletions, dangerous actions |
| **Green** | `#b9d665` | Strings, insertions, success |
| **Cyan** | `#aee6d6` | Regex, escapes, information |
| **Blue** | `#9cd9e6` | Links, properties, secondary info |
| **Purple** | `#eba4be` | Constants, numbers, booleans |

## 📦 Installation

1.  **Download** `catthode.micro` to your Micro colorschemes directory.
    
    *   **Linux/macOS:** `~/.config/micro/colorschemes/`
    *   **Windows:** `%USERPROFILE%\.config\micro\colorschemes\`

    ```bash
    # Example for macOS/Linux
    mkdir -p ~/.config/micro/colorschemes
    cp catthode.micro ~/.config/micro/colorschemes/
    ```

2.  **Activate** the theme in Micro.

    Press `Ctrl-E` in Micro to open the command bar, then type:
    ```
    set colorscheme catthode
    ```

    Or add it to your `settings.json` (usually in `~/.config/micro/settings.json`):
    ```json
    {
        "colorscheme": "catthode"
    }
    ```
