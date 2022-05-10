# TMPTest
Sample Unity 3d version 2021 project to demonstrate a bug with TMP_InputField with hide mobile keyboard setting enabled, on iOS platform.

1. Build and run project for iOS
2. Tap inputfield in scene to open touchkeyboard
3. Tap two characters at about same time, or simply spam keys to enter text.

Expected: Whatever you type is entered in the inputfield and caret stays at end of text
Actually happens: Caret doesn't always properly update to end of text, as a result the characters you enter are being input between previous characters.
