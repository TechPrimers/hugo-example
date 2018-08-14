# Hugo Example

## Setup
- Goto `https://gohugo.io/getting-started/quick-start/` for downloading Hugo CLI
- Once installed a new site can be created using Hugo CLI
```
    $ hugo new site hugo-example
```
This will create a new website with default files and folders.
- Install a theme to make the UI more appealing

## Theme Installation
To install Hyde as your default theme, first install Hyde repository in the `themes/` directory:

    $ cd themes/
    $ git clone https://github.com/spf13/hyde.git

Second, specify `hyde` as your default theme in the `config.toml` file. Just add the line

    theme = "hyde"

## Add new pages
New pages can be added using the CLI

    $ hugo new _index.md
    $ hugo new apps/store.md
    $ hugo new apps/website.md

Add content like how you add Markdown data

## Run Hugo WebServer 
Now to get the static website UP, run the hugo server

    $ hugo serve -D

The site is up at `http://localhost:1313/` by default