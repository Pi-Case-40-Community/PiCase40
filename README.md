# Pi Case 40  

Community modifications, accessories and designs for Cooler Master's Raspberry Pi Case - Pi Case 40 and its GPIO redirecting PCB  

Here is what we have so far:

 - GPIO redirection PCB replacement by [nobodypb](https://github.com/nobodypb)
 - GPIO redirection PCB replacement by [ifohancroft](https://github.com/ifohancroft)
 - Software to remap the button from CLI by [lpgera](https://github.com/lpgera)

## Housekeeping

### Cloning

Everything is included as a submodule, so clone with ```git clone --recurse-submodules --remote-submodules https://github.com/Pi-Case-40-Community/PiCase40.git``` or ```git clone --recurse-submodules --remote-submodules git@github.com:Pi-Case-40-Community/PiCase40.git``` to get the repo with the latest version of each submodule.

If you are using the GitHub cli tool, another GitHub client or you just downloaded the repo as a zip - I don't know how you can get all the latest submodules, sorry! If you do - let me know or feel free to open a PR to add it to the README. 

### Browsing

Submodules generally link to a specific commit, so while there is a way to get the latest version when cloning, this is not the case with browsing. When you click on a certain submodule, you will be redirected to its repo on that particular commit, so keep that in mind. When redirected to a repo, click its name in the top left, to start looking at its latest version.

### Staying up-to-date

To fetch any possible submodule updates, just execute ```git submodule update --recursive --remote``` in the repo's folder.
