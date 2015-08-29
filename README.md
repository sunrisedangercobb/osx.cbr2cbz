# osx_apps-cbr2cbz
Digital comic converter. Converts from .cbr format to .cbz

This is a quick and dirty little wrapper for converting digital comics.  I got tired sooooo tired of compatibility issues with readers that I decided it would be better to just convert everything.

If it is not obvious .cbr is just a .rar and .cbz is just a .zip.  So I chose to go with .zip as it is more commonly supported across readers and OSes.

#notes
This can run in single or batch mode, ff you are doing large batches I recommend commenting out notifications!  Also as this is a bash script and is more of a fire and forget, you need to kill the process from CL if you want to stop it.  This will not erase your original files, but will prompt for removal at the end.
