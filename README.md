# music.staal.io

Short links to Boris Staal's music profiles, served by GitHub Pages.

| Link | Goes to |
|---|---|
| `music.staal.io` | SoundCloud |
| `music.staal.io/soundcloud` | SoundCloud |
| `music.staal.io/spotify` | Spotify |
| `music.staal.io/apple` | Apple Music |
| `music.staal.io/amazon` | Amazon Music |
| `music.staal.io/youtube` | YouTube |
| `music.staal.io/bandcamp` | Bandcamp |
| `music.staal.io/deezer` | Deezer |
| `music.staal.io/tidal` | Tidal |
| `music.staal.io/instagram` | Instagram |
| `music.staal.io/facebook` | Facebook |

## Changing a link

1. Edit `links.tsv` (one line per link: path, label, target URL, separated by tabs).
2. Run `python3 build.py`.
3. Commit and push. The site updates in about a minute.

GitHub Pages can't send HTTP redirects, so each link is a small HTML page that
forwards the browser to its target. To change where `music.staal.io` itself
goes, set `ROOT_PATH` in `build.py`.
