# setting
```json
{
  "color_scheme": "Packages/Boxy Theme/schemes/Boxy Nova.tmTheme",
  "font_face": "monaco",
  "font_size": 14,
  "ignored_packages":
  [
    "GitGutter",
    "Vintage"
  ],
  "rulers":
  [
    80,
    120
  ],
  "tab_size": 2,
  "theme": "Boxy Nova.sublime-theme",
  "translate_tabs_to_spaces": true,
  "word_wrap": false,
  "ensure_newline_at_eof_on_save": true,
  "trim_trailing_white_space_on_save": true
}
```

# Package Control
```bash
import urllib.request,os,hashlib; h = '6f4c264a24d933ce70df5dedcf1dcaee' + 'ebe013ee18cced0ef93d5f746d80ef60'; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); urllib.request.install_opener( urllib.request.build_opener( urllib.request.ProxyHandler()) ); by = urllib.request.urlopen( 'http://packagecontrol.io/' + pf.replace(' ', '%20')).read(); dh = hashlib.sha256(by).hexdigest(); print('Error validating download (got %s instead of %s), please try manual install' % (dh, h)) if dh != h else open(os.path.join( ipp, pf), 'wb' ).write(by)
```

# packages
+ git
+ gitGutter
+ Boxy Theme
+ Doc​Blockr
+ Emmet
+ Sass
+ BracketHighlighter
+ Js​Format

+ wxapp
press `Alt + m` to show Console

+ All Autocomplete1


# Emmet
## Available actions
+ Expand Abbreviation – Tab or Ctrl+E
+ Interactive “Expand Abbreviation” — Ctrl+Alt+Enter
+ Match Tag Pair Outward – ⌃D (Mac) / Ctrl+, (PC)
+ Match Tag Pair Inward – ⌃J / Shift+Ctrl+0
+ Go to Matching Pair – ⇧⌃T / Ctrl+Alt+J
+ Wrap With Abbreviation — ⌃W / Shift+Ctrl+G
+ Go to Edit Point — Ctrl+Alt+→ or Ctrl+Alt+←
+ Select Item – ⇧⌘. or ⇧⌘, / Shift+Ctrl+. or Shift+Ctrl+,
+ Toggle Comment — ⇧⌥/ / Shift+Ctrl+/
+ Split/Join Tag — ⇧⌘' / Shift+Ctrl+`
+ Remove Tag – ⌘' / Shift+Ctrl+;
+ Update Image Size — ⇧⌃I / Ctrl+U
+ Evaluate Math Expression — ⇧⌘Y / Shift+Ctrl+Y
+ Reflect CSS Value – ⇧⌘R / Shift+Ctrl+R
+ Encode/Decode Image to data:URL – ⇧⌃D / Ctrl+'
+ Rename Tag – ⇧⌘K / Shift+Ctrl+'

Increment/Decrement Number actions:
+Increment by 1: Ctrl+↑
+Decrement by 1: Ctrl+↓
+Increment by 0.1: Alt+↑
+Decrement by 0.1: Alt+↓
+Increment by 10: ⌥⌘↑ / Shift+Alt+↑
+Decrement by 10: ⌥⌘↓ / Shift+Alt+↓
