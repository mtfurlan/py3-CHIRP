# py3-CHIRP
A fork of CHIRP for testing with Python 3.

## What's Different?
The official CHIRP project's main branch does not support Python 3 and depends on pygtk which hasn't seen a stable release since April 2011.

py3-CHIRP is a fork of the py3 branch of the official CHIRP project with some syntax fixes that seem to be leftover from Python2.

## Dependencies

py3-CHIRP has been tested in Python3.9 on various platforms. Known dependencies that don't come out of the box with Python are as follows:
- pyserial
- wxpython
- future
- six
- pypiwin32 (for Windows)

## Testing

Depending on the platform you're testing on, you should use a different script to start CHIRP.

### Linux & MacOS
`chirpw`

### Windows
`chirpwx.py`


## The Story

When I first started using Gentoo again CHIRP was still a part of the main Gentoo Portage Repository.

Eventually Gentoo began migrating away from Python2 and due to a lack of movement in the official project it was removed from the official Gentoo repository. 

I still needed to configure my radios and maintain an up to date Gentoo desktop so I cloned the py3 branch from the official CHIRP project and fixed a few syntax errors leftover from Python2 and everything worked great.

I was able to download an image from my BF-F8HP, fully reconfigure it and upload the new image back to my radio. 


### Repo Source (Forked From)

 - Mercurial Repository: http://d-rats.com/hg/chirp.hg
 - Revision: py3
 - Number:	3351:68534f20c141

### Bugs and Patches Submitted to Official Project

 - https://chirp.danplanet.com/issues/8475 - Fixed old  Python2 Syntax

### Related Bugs in Gentoo

 - https://bugs.gentoo.org/708304 - Removed CHIRP from Portage

