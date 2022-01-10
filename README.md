# mp3organizer

> NOTE: it requires [mediainfo](https://mediaarea.net/en/MediaInfo) to run and uses GNU Core Utilities commands `find`, `sed`, `grep`, `tail`, `cut` etc.

```sh
pacman -S mediainfo
apt install mediainfo
```

## Installing

For the current user:

```sh
curl https://raw.githubusercontent.com/shivajichalise/mp3organizer/main/mp3organizer > ~/usr/local/bin/mp3organizer && chmod +x ~/usr/local/bin/mp3organizer
```

Or simply copy the `mp3organizer` file to a location in your `$PATH` and make it executable.

## Usage

- run `mp3organizer` on the directory where your music files are
- done

> NOTE: this script only looks for .mp3 and .m4a on current directory

## Self-Promotion

Star the repository on [Github](https://github.com/shivajichalise/magnet)
Follow [shivajichalise](http://shivajichalise.com.np) on [Github](https://github.com/shivajichalise)

## License

This project is licensed under [GPL-3.0](https://www.gnu.org/licenses/gpl-3.0.en.html)
