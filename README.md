# Code-Highlighter
```markdown
# Academy Code Highlighter

A lightweight, modern WordPress plugin that beautifully highlights code snippets using Prism.js with a professional dark theme, line numbers, and a built-in copy-to-clipboard button.

Perfect for educational websites, programming tutorials, tech blogs, and any site that regularly features code examples.

**Version:** 1.1.2  
**Requires at least:** WordPress 5.0  
**Tested up to:** WordPress 6.6  
**Stable tag:** 1.1.2  
**License:** GPLv2 or later  
**License URI:** https://www.gnu.org/licenses/gpl-2.0.html  
**Contributors:** jules  + Grok 
**Tags:** code, syntax highlighter, prism, dark theme, copy to clipboard, developer tools, education  

## Description

The **Academy Code Highlighter** plugin transforms plain code blocks into clean, readable, and interactive snippets using the popular [Prism.js](https://prismjs.com/) library.

Designed specifically for educational and tutorial-focused sites (like https://academy-tech.ir/), it provides:

- **Modern dark theme** ("Tomorrow Night") for excellent readability
- **Line numbers** enabled by default
- **Copy to Clipboard button** (subtle on hover, shows "Copied!" feedback)
- **Automatic detection** of standard `<pre><code>` blocks
- **Default language: Python** (ideal for sites with heavy Python content)
- **Full support** for multiple languages including Python, C, MATLAB, PHP, JavaScript, CSS, and HTML
- **Shortcode support** for easy embedding
- **Performance-optimized**: Assets loaded only when code blocks are present
- **CDN-powered**: Uses reliable jsDelivr CDN for fast, up-to-date Prism.js delivery

No configuration needed — activate and go!

## Features

- Beautiful **Tomorrow Night** dark theme
- Automatic syntax highlighting for common languages
- Line numbers for professional tutorial appearance
- One-click **Copy to Clipboard** with visual feedback
- Works seamlessly with Gutenberg, Classic Editor, and shortcodes
- Defaults to Python highlighting when no language is specified
- Lightweight and fast — no bloat

## Installation

1. Download the plugin ZIP file.
2. In your WordPress dashboard, go to **Plugins > Add New > Upload Plugin**.
3. Upload the ZIP and click **Install Now**.
4. Activate the plugin.

**Or manually:**

1. Extract the `academy-code-highlighter` folder.
2. Upload it to `/wp-content/plugins/` via FTP.
3. Activate through the **Plugins** menu in WordPress.

## Usage

The plugin works automatically with standard WordPress code formatting.

### Gutenberg (Block Editor)

1. Add a **Code** block.
2. Paste your code.
3. (Optional) In the block settings sidebar → **Advanced** → **Additional CSS class(es)**, add `language-python`, `language-c`, `language-matlab`, etc.
4. Publish — highlighting is applied automatically.

### Classic Editor

Switch to the **Text** (HTML) tab and wrap your code like this:

```html
<pre><code class="language-python">
def hello_world():
    print("Hello from Academy!")
</code></pre>
```

### Shortcode (Works in Any Editor)

```shortcode
[code language="c"]
#include <stdio.h>

int main() {
    printf("Hello, World!\n");
    return 0;
}
[/code]
```

Omit the language for Python default:

```shortcode
[code]
print("This will be highlighted as Python")
[/code]
```

## Supported Languages

- Python (default)
- C
- MATLAB
- PHP
- JavaScript
- CSS
- HTML/XML
- Markup templating (for embedded code)

## Screenshots

*(Add actual screenshots here in your repository under `/assets/`)*

1. `screenshot-1.png` – C code example with line numbers and copy button
2. `screenshot-2.png` – Python code with nested quotes preserved
3. `screenshot-3.png` – Dark theme in action on a tutorial page

## Changelog

### 1.1.2
- Critical fix: Resolved fragmented per-line backgrounds and missing syntax highlighting
- Fully implemented Tomorrow Night dark theme with complete colorization
- Unified single code block container
- Line numbers, copy button, and subtle box-shadow working perfectly

*(See `changelog.md` for full history)*

## Frequently Asked Questions

**Do I need to configure anything?**  
No! The plugin works out of the box.

**Can I use a different theme?**  
Currently uses Tomorrow Night for consistency. Future versions may add theme options.

**Is it compatible with page builders?**  
Yes — works anywhere standard `<pre><code>` markup is used.

## Support & Contributions

Found a bug? Have a feature request?  
Please open an issue on the [GitHub repository](https://github.com/A.Babaei/code-highlighter).

Contributions are welcome!

---

Thank you for using **Academy Code Highlighter** — making code beautiful, one tutorial at a time! 🚀
```
