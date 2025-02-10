# SplashScreenKit
### A New Splash Screen for SwiftUI

<img width="1585" alt="Screenshot 2025-02-10 at 8 18 53 PM" src="https://github.com/user-attachments/assets/7f35a079-f74d-4c35-8f25-ea3239cc645f" />

## Version
**1.0.0 (Early Preview)** <br>
*⚠️ Various issues existed, not suitable for production environment!*

## Features
- Drop Transition
- Auto Rotation with paging
- Text Effect
- Text Transition
- Fade-in/out Transition/Animation

## Environment / Tested on
- 📲 iOS18+ required
- Swift 6.0
- iPhone 16 Pro / Pro Max
- Xcode 16.2 (16C5032a)

## Beautiful Previews
- AppleTV
- FinalCutCamera
- FindMy
- Journal

## Known Issues
**Major**
- Gesture is **disabled** due to multiple bugs
  - Dragging-left is not working due to offset; and
  - Dragging-right works but failed the ```currentIndex```
- Only compatible with iOS18+, like Apple Invites app
- Only tested on iPhone 16 Pro/Pro Max (Resize problem on small devices)
- Possible memory leakage when insert too many items into array

**Minor**
- The auto-rotation+paging feels like a "Conveyor belt sushi 🍣", not so smooth.

## Copyright
App Store Screenshots © 2025 Apple Inc.

## Reference
https://developer.apple.com/documentation/swiftui/creating-visual-effects-with-swiftui

## Related Posts on X
https://x.com/1998design/status/1888641485303878110
