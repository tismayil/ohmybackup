# ohmybackup
ohmybackup - Scan Victim's Backup Directories & Backup Files

[![asciicast](https://asciinema.org/a/KqJidcE8HewnNwGjop8AanycO.svg)](https://asciinema.org/a/KqJidcE8HewnNwGjop8AanycO)

### ohmybackup #

Scans backup folders on target sites. Searches archived files in the folders it finds.
With the 2-file scanning system, it adds extensions and filenames in different ways, making it more likely to be found.

1 - files/extensions.txt - This adds new extensions to the file, for example: by adding in the form of .example allows you to retry all the possibilities tried in the new extensions.

2 - files/files.txt - It can scan these folders according to the extensions you added, by giving them new file names.

3 - files/folders.txt - Recursively scans the specified folders. You can add to this list yourself.


## Installation

`go run ohmybackup.go --hostname victim.host`

or 

`go build ohmybackup.go`

## Run

`./ohmybackup --hostname victim.host `

