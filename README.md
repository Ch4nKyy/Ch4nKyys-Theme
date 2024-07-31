# README

My personal VS Code theme.

I use it for all sorts of languages, mainly C++ and Python, but also Rust, C#, Lua,
JavaScript/TypeScript, Java/Kotlin, etc. Some features like parameter highlighting are dependant on
the token provider of the language and might not be available for all.

I started to use VS Code profiles to reduce active extensions and thus loading times and
notifications. In the past, I could use my custom theme offline. But when using profiles on both
Windows and Linux, this seems to bug. That is why I publish my theme to the marketplace now.

## Colors

Light theme! Dark themes only make sense in a dark environment, and you should never work in a dark
environment. When it is bright outside, dark themes will create much more reflection on the screen
and make everything harder to read. Also, there are many websites and tools that do not have a dark
mode and this contrast will blind you. When it is dark outside, turn on the lights in your room. If
you are blinded by your screen, turn down the brightness. Most monitors come with a crazy high
default brightness to show off the colors.

Being able to distinguish types, functions and variables just by their color is absolutely massive.
Regexes are also much clearer with this theme. All colors have a good contrast against each other
and the background.

Classes and Types: Cyan

Functions: Blue (Declarations and definitions are underlined, calls are not)

Variables: Black (Parameters are bold)

Keywords: Green

Strings: Orange

Numbers: Red (Makes you very aware of magic numbers and null lol)

Comments: Grey (Easier to distinct from code then)

Namespaces: Grey (Reduces visual clutter and helps focusing on the relevant part of the thing)

## Development

In VS Code, use command ">Developer: Inspect Editor Tokens and Scopes" to analyze scopes.

https://code.visualstudio.com/api/extension-guides/color-theme
