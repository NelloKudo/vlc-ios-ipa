# vlc-ios-ipa

Builds the latest git version of [vlc-ios](https://code.videolan.org/videolan/vlc-ios) and packages it as an unsigned `.ipa`.

Grab it from the artifacts of any run under [Actions](../../actions). You need to be logged into GitHub to download those, and they get cleaned up after 30 days.

The ipa isn't signed, so use something like SideStore, AltStore or your own cert to install it.

It builds the `VLC-iOS-no-watch` scheme, so there's no Apple Watch app in there. You can't really sideload one anyway.

Builds run every night and can also be kicked off by hand from the Actions tab.
