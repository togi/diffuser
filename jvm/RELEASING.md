Releasing
========

NOTE: this process requires you to have a git remote named `upstream` pointing to the main repo (https://github.com/spotify/diffuser).

 1. Checkout latest master
 1. Make sure you are on a clean master and everything is pushed to upstream.
 1. Run `./gradlew clean test` and make sure everything passes.
 1. Run `./gradlew release` and follow the instructions.
 1. Enter the release version when prompted or press Enter for default (Please double check the version if you do so).
 1. Enter the next development version when prompted or press Enter for default (Please double check the version if you do so).
