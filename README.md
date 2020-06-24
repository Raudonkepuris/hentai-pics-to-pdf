# Automatic folders of hentai to one pdf file script

## What this script does

When you provide the script with a path to folder with your hentais in picture format it puts them all in a list, sorts them by name (because hentais from [nhentai](https://nhentai.net/) have names as their page number). After that a pdf document is created in memory and for every image in that list a page is created with the same resolution as the current picture and after the page is created a picture is appended to that page. It gets saved to the path you provided with the name you provided

## Installation
#### Linux
```
chmod +x install.sh
./install.sh
```

## Usage

```
hentaitopdf -m /absolute/path/to/your/hentai name
```

or

```
hentaitopdf -m relative/path/to/your/hentai name
```

or use -mc to run the script in the current folder

```
hentaitopdf -mc name
```
