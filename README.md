# Google Keep Desktop OSX
A Super Simple Desktop Client for Mac OSX Built in Javascript and MacGap

# Why
I love the Google suite but hate being limited to having to use their apps within my browser.  If you have many tabs, it's impractical for usability.

# What
It's one line of code to wrap Google Keep in an app window made possible by [MacGap](https://github.com/MacGapProject/MacGap2)

# Build
Build using instructions on [MacGap-rb](https://github.com/maccman/macgap-rb)

### Usage

    gem install macgap
    
    # macgap new DIR
    # macgap build DIR
    
For example, to create a new MacGap app use the `new` command:

    macgap new DesktopKeep
    
To build a MacGap app use the `build` command, specifying the app's directory.
    
    macgap build DesktopKeep

***Note: I'd recommend against using the binary releases at this point.  There have been issues with people downloading them and using them on different versions of OSX from what I've compiled them on and it causing problems.***

*That is, me compiling on whatever version of OSX I'm running can cause problems for you if you aren't running on the same version.  As I'm not sure what the future holds in terms of me or users of the app being up to date on the latest OSX, I'm just going to stop making releases for the foreseeable future and avoid issues.*

*Building from source following the directions in the instructions is the definite recommended method.*

# Run
Click the pretty icon :)

# Troubleshooting
Some Quarantine/Gatekeeper issues have been reported with regard to using the binaries on the release page.  As mentioned above, please build from source as this should prevent any issues.  If you're determined to use the binary on the release page, you may try (as per @gregglind):
```
# assuming you moved the app bundle to /Applications
sudo xattr -r -d com.apple.quarantine /Applications/Desktop-Google-Keep-OSX.app
```

# More
Check out the [project page](https://chriskol.github.io/Desktop-Google-Keep-OSX/) for latest release binaries and stuff.

Also check out the same thing for Google Docs at [Google Docs Desktop OSX](https://github.com/chriskol/Google-Docs-Desktop-OSX) or its [project page](https://chriskol.github.io/Google-Docs-Desktop-OSX/) for latest binaries here

Also check out the same thing for Google Drive at [Google Drive Desktop OSX](https://github.com/chriskol/Google-Drive-Desktop-OSX).
