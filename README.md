# clip room.

A public collection of music clips with embedded previews, artist filters, source credits, and MP4 download links.

**[Open the gallery](https://animvsh.github.io/clip-room/)** · **[Video library](https://github.com/animvsh/clip-room/releases)**

## Watch and download

Previews start muted. Use the video controls to listen, and choose **Download MP4** to save a clip. Artist filters, song search, and sorting help find a specific moment. New artists appear in the filters as their clips enter the public collection; the original seven artists remain in their familiar order.

Each clip includes its original source and a caption status. Editorial captions are commentary rather than lyrics; automatic captions are identified separately.

## Publication

GitHub Pages serves the root of the main branch. Videos are immutable GitHub Release assets; this repository contains the gallery, public catalog, posters, subtitles, and posting captions.

The catalog is refreshed daily with newly finished clips. Publication requires the current artist-name and alien-watermark finish, checked media, and no active quality or caption-review hold. Earlier video links remain available when a revised edit is published.

Production credentials, source media, and private download records are kept outside this repository. See the [release notes](CHANGELOG.md) for changes.

## Development

This is a buildless HTML, CSS, and JavaScript site. Serve the repository directory with any static HTTP server, for example:

```sh
python3 -m http.server 8000
```

The public catalog is in data/clips.json. It contains only public clip metadata and links; do not add credentials, personal records, or production paths.

## Credits

These are fan-made edits. Music and original footage remain credited to their respective artists and creators; original-source links are provided on each clip.
