gDriveLink
==========

Simple script to change a google drive link to a direct download or view link

Store the bash script gDriveLink to /usr/local/bin and 
make it executable with chmod +x /usr/local/bin/gDriveLink



usage: gDriveLink

This script changes google drive share links
to links that can be directly viewed or downloaded

the new url will be returned to stdout

USAGE:
  ./gDriveLink [-d|-v|-s|-b] url(s)

OPTIONS:
  -h,--help       Show this message
  -d,--download   print the download url(default)
  -v,--view       print the view url
  -s,--suffix     append the google drive file name to the url
  -b,--both       Print both the default and the modified url
                  seperated by a tab character

