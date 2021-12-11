# fsl - File System Listener

Execute a given command when a change in files is detected

## Example

I particullary use it to reprocess lilypond files when I am editing
so as to not have to request a new lilypond execution every time a file
is modified (which is like every 15 seconds):

`fsl "lilypond the-main-file.ly" *.ly`

## License

fsl is released under the terms of GPLv3

## Bugs

- If the command provided uses filenames that have white spaces in their names, it fails

Edmundo Carmona Antoranz
Costa Rica 2021

