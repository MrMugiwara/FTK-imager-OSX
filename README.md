# FTK-Imager-OSX
FTK Imager a Forensics Tools For MAC OS X
# Install FTK Imager For Mac OS 

git clone git@github.com:MrMugiwara/FTK-Imager-OSX.git<br>

cd FTK-Imager-OSX<br>

chmod +x ftkimager<br>

./ftkimager -h<br>


# Usage For FTK Imager

Usage:  ftkimager source [dest_file] [options] <br>

AccessData FTK Imager v3.1.1 CLI (Aug 24 2012) <br>
Copyright 2006-2012 AccessData Corp., 384 South 400 West, Lindon, UT 84042 <br>
All rights reserved.<br>

Usage:  ftkimager source [dest_file] [options] <br>
source can specify a block device, a supported image file, or `-' for stdin<br>
if dest_file is specified, proper extension for image type will be appended<br>
if dest_file is `-' or not specified, raw data will be written to stdout<br>
Options:<br>
  --help        : display this information<br>
  --list-drives : show detected physical drives<br>
  --verify      : hash/verify the destination image,<br>
                  or the source image if no destination is specified<br>
  --print-info  : print information about a drive or image and then exit<br>
  --quiet       : do not show create/verify progress information<br>
  --no-sha1     : do not compute SHA1 hash during acquire or verify<br>
(The following options are valid only when dest_file is specified):<br>
  --s01         : create a SMART ew-compressed image<br>
  --e01         : create an E01 format image<br>
  --frag x{K|M|G|T} : create image fragments at most x {K|M|G|T} in size<br>
                  also accepts kB, MB, GB, and TB for powers of 10 instead of 2<br>
  --compress C  : set compression level to C (0=none, 1=fast, ..., 9=best)<br>
  e01/smart metadata (use quote marks when X contains spaces):<br>
    --case-number X<br>
    --evidence-number X<br>
    --description X<br>
    --examiner X<br>
    --notes X<br>
AD Encryption Options:<br>
  --inpass P      : decrypt source file using password P<br>
  --incert C [P]  : decrypt source file using certificate C with password P<br>
  --outpass P     : encrypt dest file using password P<br>
  --outcert C [P] : encrypt dest file using certificate C with password P<br>

