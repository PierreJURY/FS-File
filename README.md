# FS File

FS File est un outils web qui permet de partager facilement des fichiers sur internet.
Il est idéal pour le mettre en place sur un serveur afin d'avoir un accès à ces fichiers partout

## Fonctionnalité

- Import a HTML file and watch it magically convert to Markdown
- Drag and drop images (requires your Dropbox account be linked)
- Import and save files from GitHub, Dropbox, Google Drive and One Drive
- Drag and drop markdown and HTML files into Dillinger
- Export documents as Markdown, HTML and PDF

## Installation

FS-File requière [PHP](https://php.net/), il à été développer sur la version 8.1

Pour mettre en place le site, vous devez simplement copier les fichiers du site dans le répertoire de votre choix

```sh
cd /votre/repertoire
git clone https://raw.github.com/pierrejury/fs-file
```

## Configuration

Le fichier de configuration se trouve dans /config/config.php

| Plugin | README |
| ------ | ------ |
| Dropbox | [plugins/dropbox/README.md][PlDb] |
| GitHub | [plugins/github/README.md][PlGh] |
| Google Drive | [plugins/googledrive/README.md][PlGd] |
| OneDrive | [plugins/onedrive/README.md][PlOd] |
| Medium | [plugins/medium/README.md][PlMe] |
| Google Analytics | [plugins/googleanalytics/README.md][PlGa] |

## License

Gratuit et open source !
