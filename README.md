# checkra1n-linux
## a simple all-architecture checkra1n installer
Works on x86, x86\_64, ARM and ARM64!
By [Randomblock1](https://twitter.com/randomblock1)

## one liner
run without installing:
`curl -s https://raw.githubusercontent.com/Randomblock1/checkra1n-linux/master/installer.sh | sudo bash`
(note: you can't use procursify unless you actually install it)

## install
`git clone https://github.com/Randomblock1/checkra1n-linux && cd checkra1n-linux`

`./installer.sh`

## how to use
- "Install Repo"
  - This will install the checkra1n APT repo, but only if you are using x86\_64.
- "Direct Download"
  - Installs checkra1n to /usr/bin for all devices, regardless of architecture.
- "Procursify"
  - Installs the Procursus bootstrap to your device. Learn more about Procursus [here](https://github.com/ProcursusTeam/Procursus). TLDR: Replaces Substrate with libhooker and uses the Procursus repo for more up-to-date programs. Also, you get Sileo, in addition to Cydia.
- “Save Blobs”
  - Saves signed SHSH blobs so you can upgrade/downgrade to unsigned iOS versions if you've saved your blobs.
- "Credits"
  - Is self explanatory
- "Update"
  - Uses curl to get the latest version of this tool. You shouldn't need to use this, as it updates itself on startup.

If you are not on a Debian based system, you may need to install dependencies manually. Just Google any errors and see if it means you're missing something.

Please put any issues in the GitHub Issue tracker and feel free to make pull requests.

## todo
add support for systems that are not Debian or OSX
