# Collaborative Compositions

This is a project in which we can write songs collaboratively.
being primarily software developers, we are most comfortable working as a team through version control. let's leaverage it to write music together!

## Why Git
discussions and alterations to code occurs through pull requests. well, VCV Rack files are simply JSON files, so why not do the same methodology to compose tracks together as well?


## Getting Started

* Each song should have its own branch while in development.

* Each song should be created in its own folder with one .vcv file, and a file containing information about the track such as { lead author, scope, intent, plugins }

* When a song is ready for release, add an audio file to the folder and submit a PR to merge to master.
    * TODO: when a song is merged to master, can it be deployed to soundcloud through API?

## Cooperative guidelines

Much like code, if you see or hear something that doesn't quite fit with the intent of the track, bring it out in the PR, submit a PR of your own to alter it, etc.

### Limitations

in an effort to ensure everyone can participate without having special audio equipment, the following restrictions are suggested

* Tracks should be no more than two channels

* All sound is generated in VCV rack. No input from external hardware or VST instruments

* Only use free modules

* Voices, patterns, and other such multi-module patches should be surrounded on either side with matching blank panels to help isolete them visibly. If you see any modules in this arrangement, avoid modifying or tying into them in order to keep instruments of a track decoupled.