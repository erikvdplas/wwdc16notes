# What’s new in Swift

## Goals
- Portability to new platforms
- Awesomeness

## Apple’s Usage of Swift
- Music
- Console
- Parts of Xcode
- Swift Playgrounds for iPad
- Dock

## Dock Case Study
Dock is about 200.000 lines of code.
Compared to El Capitan it contains 2.5x more Swift code and there’s a huge decrease in the amount of lines although it contained more features.

## Swift Open Source (swift.org)
Why?
- Open evolution process
- Non-Apple contributors with direct commit access
- Code of conduct
- Apache 2 with Runtime Library Exception
Development is on GitHub, three main categories of projects:
- Language
- Package Manager
- Standard Libraries

The language category contains the swift-evolution repo. This is meant for making changes in Swift: first changes are discussed and then proposals are made, by reviewing the proposals the pull requests are accepted, the discussing continues on the mailing list. A Core Team arbitrates a decision and decides wether or not it should be implemented in the 'official' version of Swift.

## What’s new in Swift 3
API naming:
Apple (and the open source community) studied whats important in API design:
- Clarity
- Consistency
- Reduce Complexity

## Type System:
Updates on IUO

Standard Libraries:
FloatingPoint unifies Float, Double, Float80 and CGFloat.
Swift 3 contains Float.pi. To remain compatibility with other FloatingPoints you can simply use .pi.

Tools
Slower compiling due to module-optimisation but improved caching (and therefore faster compiling after first compilation).

## Swift 2.3
= Swift 2.2 + compatibility with new SDK’s
