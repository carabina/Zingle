# Zingle

Zingle – An alert will display underneath your UINavigationBar 🎅

[![Build Status](https://travis-ci.org/hemangshah/Zingle.svg?branch=master)](https://travis-ci.org/hemangshah/Zingle)
![License](https://img.shields.io/badge/License-MIT-lightgrey.svg)
![Platform](https://img.shields.io/badge/Platforms-iOS-red.svg)
![Swift 4.x](https://img.shields.io/badge/Swift-4.x-blue.svg)
![MadeWithLove](https://img.shields.io/badge/Made%20with%20%E2%9D%A4-India-green.svg)
[![Blog](https://img.shields.io/badge/Blog-iKiwiTech.com-blue.svg)](http://www.ikiwitech.com)

1. [Screenshots](#screenshots)
2. [Features](#features)
3. [Installation](#installation)
4. [Setup](#setup)
5. [Credits](#credits)
6. [Thanks](#thank-you)
7. [License](#license)

## Screenshots

<table>
<tr>
<td align="center"><img src = "https://github.com/hemangshah/Zingle/blob/master/Screenshots/Screenshot-1.png" alt = "iPhone8+"></td>
<td align="center"><img src = "https://github.com/hemangshah/Zingle/blob/master/Screenshots/Screenshot-2.png" alt = "iPhoneX"></td></tr>
<tr><td align="center" colspan="2"><img src = "https://github.com/hemangshah/Zingle/blob/master/Screenshots/Screenshot-1-landscape.png" alt = "Landscape"></td></tr>
</table>

## Features

1. Easy to setup & Use
2. Dynamic Property Configurations.
3. Lightweight with zero dependancies.

## Installation

1. **Manually** – Add `Zingle.swift` file to your Project.<br>
2. **CocoaPods** – `pod 'Zingle'`
    
> You can read the [CHANGELOG](https://github.com/hemangshah/Zingle/blob/master/CHANGELOG.md) file for a particular release.

## Setup

````
Zingle.init(duration: 0.5, delay: 3)
  .message(message: "No Internet Connection.")
  .messageIcon(icon: #imageLiteral(resourceName: "warning-icon"))
  .messageColor(color: .white)
  .messageFont(font: UIFont.init(name: "AmericanTypewriter", size: 15.0)!)
  .show()
````

You can [watch](https://github.com/hemangshah/Zingle/subscription) to <b>Zingle</b> to see continuous updates. Stay tuned.

<b>Have an idea for improvements of this class?
Please open an [issue](https://github.com/hemangshah/Zingle/issues/new).</b>
    
## Credits

<b>[Hemang Shah](https://about.me/hemang.shah)</b>

**You can shoot me an [email](http://www.google.com/recaptcha/mailhide/d?k=01IzGihUsyfigse2G9z80rBw==&c=vU7vyAaau8BctOAIJFwHVbKfgtIqQ4QLJaL73yhnB3k=) to contact.**
   
## Thank You!!

See the [contributions](https://github.com/hemangshah/Zingle/blob/master/CONTRIBUTIONS.md) for details.

## License

The MIT License (MIT)

> Read the [LICENSE](https://github.com/hemangshah/Zingle/blob/master/LICENSE) file for details.
