# nfTools Editor Themes

### Simple & modern themes for Visual Foxpro Editor

![](https://github.com/nftools/EditorThemes/blob/master/DarkFox.jpg)

**Steps:**

- Install Font "Roboto Mono" from [https://github.com/google/fonts/raw/master/apache/robotomono/RobotoMono-Regular.ttf](https://github.com/google/fonts/raw/master/apache/robotomono/RobotoMono-Regular.ttf)
- Use Import -> Select your theme file settings **"DarkFox-Vfp9-Editor-Theme.txt"**
- Restart Vfp or use SYS(3056) from the command window to reload registry settings.

Note:
- If you want to go back to default vfp values: go to /Main Menu/Tools/Options/Editor-> "Reset All" & "set as default"
- If you have a current color set different from default, you can save it before making changes: open Regedit and go to   **HKEY_CURRENT_USER\Software\Microsoft\VisualFoxPro\9.0\Options**  right click -> "export". Then just open the resulting .reg file to set back your values.
