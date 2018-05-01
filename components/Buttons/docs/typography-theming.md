<!--docs:
title: "Typography Theming"
layout: detail
section: components
excerpt: "How to theme Buttons using the Material Design typography system."
iconId: button
path: /catalog/buttons/typography-theming/
-->

# Buttons Typography Theming

You can theme buttons with your app's typography scheme using the TypographyThemer extension.

You must first add the Typography Themer extension to your project:

```bash
pod 'MaterialComponents/Buttons+Extensions/TypographyThemer'
```

## Example code

<!--<div class="material-code-render" markdown="1">-->
#### Swift
```swift
// Step 1: Import the TypographyThemer extension
import MaterialComponents.MaterialButtons_TypographyThemer

// Step 2: Create or get a typography scheme
let typographyScheme = MDCTypographyScheme()

// Step 3: Apply the typography scheme to your component
MDCButtonTypographyThemer.applyTypographyScheme(typographyScheme, to: component)
```

#### Objective-C

```objc
// Step 1: Import the TypographyThemer extension
#import "MaterialButtons+TypographyThemer.h"

// Step 2: Create or get a typography scheme
id<MDCTypographyScheming> typographyScheme = [[MDCTypographyScheme alloc] init];

// Step 3: Apply the typography scheme to your component
[MDCButtonTypographyThemer applyTypographyScheme:colorScheme
     toButton:component];
```
<!--</div>-->