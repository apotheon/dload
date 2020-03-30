# DLoad

DLoad is a command line utility for Unix-like environments that uses curl to
download a file based on URIs in the X selection or clipboard.  It is designed
to avoid overwriting existing files by accident due to filename duplication.
In other words, DLoad is a curl-based overwrite-avoiding paste-aware CLI
downloader.

## Current Status

It presently requires download URIs as command line arguments to find the file
for download.  This effectively duplicates the behavior of a preceding shell
script implementation, with some minor improvements.

## Roadmap

* Add support for reading URIs from X selections and clipboard.
* Add checksum support for autodeleting duplicate files upon download.
