# HPC-stack-NOAA-blocked-downloads
A few downloads that are blocked by the firewall to be downloaded to some of the NOAA systems
Need to use git-lfs extension of git: https://git-lfs.github.com/
Installed on a Mac using Homebrew:
brew install git-lfs

Run (an example):
git lfs install  (run only once per git account)
git lfs track "*.psd"  (to track files with *.psd extension, for instance)
git add .gitattributes
git add file.psd
git commit -m "Add design file"
git push origin main


05/17/2022 added:
wgrib2.tgz.v2.0.8
madis-4.3.tar.gz
