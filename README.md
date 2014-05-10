# Alfred-Backblaze

An [Alfred 2](http://www.alfredapp.com/) workflow to Pause and Sync [Backblaze](http://www.backblaze.com/) online backups.

## Install

Download and open [Backblaze.alfredworkflow](Backblaze.alfredworkflow) using [Alfred 2](http://www.alfredapp.com/).

## Use

Type the keyword 'bz' followed by either 'Pause' or 'Sync'.

## About

This workflow simply runs '/Library/Backblaze.bzpkg/bztransmit -pausebackup' and '/Library/Backblaze.bzpkg/bztransmit -completesync' for pausing and initiating sync, respectively.

The [Alfred-Workflow](http://www.deanishe.net/alfred-workflow/) python library is used for interface feedback and query filtering.

## License

[MIT License](http://zenorocha.mit-license.org/)
