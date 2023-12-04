# palera1n jailbreak

palera1n is one of the current tools to jailbreak (selected) iPhones.

The official website > [palera1n](https://github.com/palera1n/palera1n)

The documents can be found > [ios.cfw.guide](https://ios.cfw.guide/)

Specific information about setting up rootful jailbreak > [Rootful jailbreak](https://ios.cfw.guide/archived-palera1n-rootful/)


[ Pre-requsites ]
1. macOS on desktop or laptop
2. homebrew installed
3. python3 installed (either by macOS or homebrew)
4. iPhone supported by palera1n
5. . Genuine USB -A to Lightning cable

[ homebrew setup ] 
Refer to https://brew.sh for setup instructions

[ Installing palera1n ]
Finder > Applications > Utilities > Terminal

`mkdir palera1n && cd palera1n`
`python3 -m venv .`
`source bin/activate`
`pip install palera1n`

Now you're set.

## Jailbreaking the iPhone

Decide whether would you want a rootful or rootless jailbreak.

For rootful jailbreak
Still in Terminal or go to Terminal (Finder > Applications > Utilities)
`cd palera1n`
`./palera1n  -c -f`

For rootless jailbreak
Still in Terminal or go to Terminal (Finder > Applications > Utilities)
`./palera1n`

## How to re-jailbreak

For rootful jailbreak
Still in Terminal or go to Terminal (Finder > Applications > Utilities)
`cd palera1n`
`./palera1n  -f`

For rootless jailbreak
Still in Terminal or go to Terminal (Finder > Applications > Utilities)
`cd palera1n`
`./palera1n`


In both rootful or rootless jailbreaks, you will experience a hang on the phone (A9 or below) and when the terminal is showing Booting PongOS
1. Keep the usb cable connected, hit Ctrl+C on the terminal and 
2. Rerun the same palera1n command with the same options.

Notes: For rootful jailbreak, it will take at least 15 minutes to build the fakefs. So let the phone run.
