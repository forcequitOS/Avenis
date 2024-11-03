# Avenis
Check your internet connection status and IP addresses across 2023 Apple platforms. Releasing in December.

<img src="https://github.com/forcequitOS/Avenis/blob/main/About%20Avenis.png?raw=true" alt="The Avenis > About page, shows app icon, version 1.0 Preview, 18 days of development time, built with Xcode 16.1" width="35%">

### Features:
- Configurable
- Fast
- Modern (iOS 18 icon theming support, watchOS 10 UI style)
- Widgets, everywhere
- Support for every Apple platform except tvOS
- No sideloading needed (For iPads with Swift Playgrounds)

### Credits:

This project used to be called Netcheck until I realized a *verrry* similar app for Apple platforms already existed called NetCheck Connectivity, go check it out [here](https://apps.apple.com/us/app/netcheck-connectivity/id1570703771), this was entirely unintentional and I did not mean to copy, whoops.

On the topic of similar apps, I'm gonna go ahead and also recommend [IsThereNet](https://github.com/FuzzyIdeas/IsThereNet), pretty cool looking app for macOS that monitors in the background!

Oh, and [r/SwiftUI](https://reddit.com/r/SwiftUI) for helping me get through some of the tougher conundrums during development, you guys rock.

For the record, I started developing Netcheck (now Avenis) around March to help me kill time and have just been struggling to complete it, but I promise I *will* do so someday soon!

Finally, the About screen is my own creation. It started as originally just an Avenis thing, but ended up having a whole separate release as a Swift Package (ironically before Avenis itself did). It's called [Summit](https://github.com/forcequitOS/Summit), use it as you wish in your apps! I may have accidentally put more effort into the about screen than I did the app itself...

### So what do I download?

Here's a chart.

| File Names        | Supported OS              | Details                                                               |
|-------------------|---------------------------|-----------------------------------------------------------------------|
| Avenis.zip        | macOS 14 Sonoma and later | Unsigned Mac .app, drag to /Applications and allow in System Settings |
| Avenis.ipa        | iOS & iPadOS 17 and later | iPhone and iPad .ipa, contains Watch app, install with AltStore       |
| AvenisLight.zip   | iPadOS 17 and later       | Swift Playgrounds .swiftpm package, exclusively for iPads             |
| AvenisExpanse.ipa | visionOS 1 and later      | Apple Vision .ipa, sideload with Sideloadly or similar tools          |

### Future Plans:

After the... actual final release of Avenis, I have two main things planned for the future. "1.5", "The Widget Update", to bring some much needed enhancements to the widgets, which will be plentiful, but a bit lacking at launch, and "2.0", "The Background Update", possibly bringing background monitoring and a menu bar extra to the Mac app. No promises, though.
