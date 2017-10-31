# GitHub Keyring Public Keyring
This is designed to store the public keys of GitHub users to authenticate that all github users submitting to the repo are infact who they say they are.

Currently this is a WIP, I have yet to write the actual plugin and add-on to handle this. **PLEASE DO NOT COMMIT AT THIS TIME.**

License is MIT for now, but in the future if this is actually popular we may need to do something to protect maintainers from liability.

Keys are signed with GPG keys. Please see Git documentation [here](https://git-scm.com/book/id/v2/Git-Tools-Signing-Your-Work).

Although you may this is unneccesary because obviously GitHub authenticates commits already ussing SSH keys. Although that's true, there are many other uses for private-public key authentication.

I'll work on this more later.
