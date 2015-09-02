# osx_apps-cbr2cbz
Digital comic converter. Converts from .cbr format to .cbz

This is a quick and dirty little wrapper (uses rar binary) for converting digital comics.  I got tired sooooo tired of compatibility issues with readers that I decided it would be better to just convert everything.

If it is not obvious .cbr is just a .rar and .cbz is just a .zip.  So I chose to go with .zip as it is more commonly supported across readers and OSes.

#notes
This can run in single or batch mode. This will not erase your original files, but will prompt for removal at the end.
This app would like to use a ruby gem called terminal-notifier.  If it is not installed it will use the basic notifications.  

If you would like to install the gem you can issue this command:
[sudo] gem install terminal-notifier
