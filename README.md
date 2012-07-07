# Alfred Extension: Open in BBEdit

This is a simple AppleScript extension for [Alfred][]
that opens in BBEdit any files or folders that are selected in the _front
window_ of the Finder. 

## Use

In the Finder, navigate to the file or folder you want to open in BBEdit. Then
invoke Alfred and enter the extension keyword "obb" to open the folder in
BBDEdit, or "obb s" to open the selected file.

By default this extension will open the current folder. If you supply an
argument of 's', then it will open **all** the files or folders selected in the
front Finder window. So you can open several files at once by multi-selecting
them in the Finder.

BBEdit is activated after it opens the items.

If there is a problem locating the front finder window or identify the current
directory or selected files, then an error is displayed using Growl. (If Growl
is not installed, no error is reported.)

## Installation

Download this repository and drag the file `Open in BBEdit.alfredextension` to
the "Drop to install" target in Alfred's "Extensions" preference pane. If you
don't like the default keyword "obb", then change it.

## Notes

1. [Alfred][] is an OS X application for launching applications and utilities.
1. The _front window_ is the window that is active when the application is
activated.
1. The [Alfred Powerpack][] is required to install Alfred extensions.

[Alfred]: http://www.alfredapp.com/
[Alfred Powerpack]: http://www.alfredapp.com/powerpack/

## Change History

* 2012.07.07 Created.