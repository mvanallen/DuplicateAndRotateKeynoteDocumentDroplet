DuplicateAndRotateKeynoteDocumentDroplet
========================================

Create a copy of a Keynote document with its content rotated by 90 degrees counterclockwise

..useful when trying out on an actual device your app prototypes made with Keynote
because Keynote for iOS is landscape only and will not display fullscreen your document made in portrait (e.g. see WWDC 2014 Session 223 [Prototyping: Fake It Till You Make It](https://developer.apple.com/videos/wwdc/2014/#223)).
 
Originally based on RotateKeynoteDocumentDroplet by ericallam, see https://gist.github.com/ericallam/a5cd76651c327b116a6e - this script simply refines his work, so kudos to him!

This fork from AdulteTerrible includes the following changes:

- fixes rotations of grouped elements (see [fix-groups](https://github.com/mvanallen/DuplicateAndRotateKeynoteDocumentDroplet/tree/fix-groups))

How to use:

1. Open Script Editor

2. Set your language to Java Script

3. Paste this code and export it as an Application

4. Drop your keynote doc on this application in the Finder
