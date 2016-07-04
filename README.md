# kaldiinstall

## Kaldi Installation
### On Arch-Linux 
**Prerequisites**
- SVN (https://www.archlinux.org/packages/?name=subversion)
- Wget

**Installation**
- Download Kaldi. Run `svn co https://svn.code.sf.net/p/kaldi/code/trunk kaldi-trunk`
- Get Updates, bug fixes. Run `svn update`

kaldi-trunk structure 

```
kaldi-trunk  (main directory)
├── COPYING 
├── egs (example scripts allowing you to quickly build ASR systems for over 30 popular speech corporas)
├── INSTALL
├── misc (additional tools and supplies, not needed for proper Kaldi functionality)
├── README.txt
├── src (Kaldi source code)
├── tools (useful components and external tools)
└── windows (tools for running Kaldi using Windows)
412 directories, 3529 files 
```
