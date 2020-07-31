# Filemark - Alfred Workflow for universal bookmark manager

<img src="https://github.com/jackchuka/alfred-workflow-bookmarks/blob/master/icon.png?raw=true" alt="logo" width="130"/>

## Installation

1. make sure you have `jq` installed, otherwise `brew install jq`.
1. download [Filemark.alfredworkflow](https://github.com/jackchuka/alfred-workflow-bookmarks/releases/latest) file.
3. update environment variable `DIR_PATH` ie. `/Users/username/Dropbox`

## Usage

#### Search
Search through all of your bookmarks by typing a keyword.
```
b {keyword}
```
![Search](https://github.com/jackchuka/alfred-workflow-bookmarks/blob/master/screenshots/screenshot_github.png?raw=true)

#### Add a bookmark
Adding an url followed by the name or keyword.
```
b add {url}
# hit enter
{keyword or name you can remember}
```
![Add](https://github.com/jackchuka/alfred-workflow-bookmarks/blob/master/screenshots/screenshot_add.png?raw=true)

#### Edit
Edit command opens the source text file.
```
b edit
```

#### Backup
Backup command will duplicate the source file with name of `backup_{filename}`
```
b backup
```
