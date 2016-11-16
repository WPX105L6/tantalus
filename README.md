# Tantalus
Run this on a network connected device, and it will automatically set up a heavily restricted jail sandbox.  No monitoring is done, nor any malicous activity.  Users that connect to the device with the generic account will have their IP logged and black listed.  Those users will be unable to do anything on the device, and will not have access to any other parts of your network.
*Note*: There is NO back door installed.  Once this program runs the ONLY account that will be able to log in is the generic one.  In order to update, you will need to reinstall the OS from a different device, then run Tantalus again.
*Another note*: This will work best when running on a fresh OS install, so that there are no permissions issues.  To rehash what was said above, if you run this on your personal device, **you will lose access to everything**.

## How do I use it?
Easy!  Just download all of the files to one directory, navigate to the directory and run `tantalus.py`.

## Progress
- [x] create ` README.md` and GitHub repo
- [ ] create an installer template
- [ ] create setup scripts as individual pieces
- [ ] link scripts to installer
- [ ] test for compatibility accross different Linux distros
