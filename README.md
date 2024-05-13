# Material views should stop listening for back callbacks when detached from window
This repository contains an android app built from the "Bottom Navigation Views Activity" template in Android Studio with a search bar added to the dashboard tab. The gesture back on the first tab does nothing when there are open search results in the second tab.

## Steps to recreate the problem
1. Tap the dashboard tab
2. Tap into the search bar so that the results and keyboard open
3. Gesture back to close the keyboard
4. Tap the Home tab
5. Gesture back should close the app but it does nothing because the search results block it
