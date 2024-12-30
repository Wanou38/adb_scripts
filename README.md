# adb_script is for ?

## For what ?

General scripts let's you see what apps are in your device and their type: user, system, disabled or removed pre-installed apps.

Android base and Google script allow you to remove base apps after you installed alternative ones.

By device scripts allow you to remove bloatware. You can add comments to preserve a particular app. Because there are plenty of manufacturers and models, help will be necessary to improve the device specific scripts.

## For who ?

Theses scripts are designed for power users only. You don't need to be neither a developer nor a command line guru.

Script are very simple and autonomous, they can be used and customized by anyone who can use a text editor to customize the scripts if needed. they dont need arguments.

# Scripts organisation

[Project's root dir]─┬─ Base universal scripts prefixed by numbers
                     ├─ [Manufacturer 1]─┬─ (optional) Base manufacturer 1 scripts prefixed by numbers
                     │                   ├─ [Device 1] ── Device 1 scripts
                     ╎                   ╎
                     │                   ╰─ [Device n] ── Device n scripts
                     ╎
                     ╰─ [Manufacturer n]─┬─ (optional) Base manufacturer n scripts prefixed by numbers
                                         ├─ [Device 1] ── Device 1 scripts
                                         ╎
                                         ╰─ [Device n] ── Device n scripts
