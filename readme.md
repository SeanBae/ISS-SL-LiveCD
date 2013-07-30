###Scientific Linux 5.5 LiveCD Creating Script
This script was written for the purpose of automatizing the Scientific Linux testing environment for the ISS-CREAM (International Space Station - Cosmic Ray Energetics And Mass) Project

By Sean Bae

----

NOTE:

- We assume you are using the Scientific Linux 5.5 environment

- Make sure you run the last command in the `chroot` environment

- Even though this script was originally written for the ISS-CREAM project, this can be used for any project that requires SL5.5 LiveCD generation

----

INSTRUCTION:

1. Open the `main` script with a text editor

2. Under the `#List of Packages` comment, customize the list of packages for your own purpose of creating liveCD

3. Execute the two commands: `chroot /scratch/livecd/` and `/build/livecd/livecd-3.1.0/build-livecd.sh`

4. Your final `.iso` image file can be found under `/scratch/livecd/tmp` after exiting chroot environment
