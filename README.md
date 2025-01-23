# Wallpapers
Wallpapers for Arcticons

## How to contribute
You will need to:
1. In `/android/`, the full-size wallpaper (JPEG for photos and photorealistic images, PNG for other graphics)
2. In `/android/.thumbs`, the thumbnail image (WEBP, 800px tall, auto width)
  * You can use [Haley's batch image converter/resizer](https://2gd4.me/tidbit/image) for this.
3. Just before the `]` at the end of the files named `/config-*.json`, the required metadata. Just follow the existing format:
```js
{
  // Your name if you made this yourself, the photographer's name if you're submitting someone else's CC0 or CC-BY photo.
  "author": "Donno",
  // The title of the wallpaper displayed in the app and on the web page.
  "name": "Black Hole",
  // The thumbnail image file that you put in /android/.thumbs/.
  "thumbUrl": "https://wallpapers.arcticons.com/android/.thumbs/blackhole.webp",
  // The full-size wallpaper image file that you put in /android/.
  // (This would end in .jpg or .jpeg instead if you're submitting a photo)
  "url": "https://wallpapers.arcticons.com/android/blackhole.png"
}
```

To make these changes, you should:
1. [fork the repository under your own account](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo)
2. pull the repo using Git in the command line or using GitHub Desktop
3. then finally [create a pull request on the source repo](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request), so that the Arcticons team can review and approve your changes.