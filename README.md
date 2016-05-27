# GitHub-Markdown-Font-Settings.tmbundle
Provides nicer fonts for the [GitHub Flavoured Markdown for TextMate bundle](https://github.com/mikemcquaid/GitHub-Markdown.tmbundle]).

## Features
- Use San Francisco for the Markdown editor font and make it match the preview size
- Use Menlo for the Markdown editor monospaced text font and make it match the preview size
- Use the default font size for the Markdown editor hash/pound prefix
- Render all Markdown editor headings the same relative size and font as in the preview

## Installation
### TextMate 2
Check "Markdown (GitHub) Font Settings" in TextMate 2's Preferences' Bundles.

Alternatively:
```bash
mkdir -p ~/Library/Application\ Support/Avian/Bundles
cd ~/Library/Application\ Support/Avian/Bundles
git clone https://github.com/mikemcquaid/GitHub-Markdown-Font-Settings.tmbundle
```

### TextMate 1
```bash
mkdir -p ~/Library/Application\ Support/TextMate/Bundles
cd ~/Library/Application\ Support/TextMate/Bundles
git clone https://github.com/mikemcquaid/GitHub-Markdown-Font-Settings.tmbundle
osascript -e 'tell app "TextMate" to reload bundles'
```

## Status
The above features are tested and working for my day-to-day.

Tested using TextMate 2. May work in TextMate 1 or Sublime Text; I've no idea.

[Patches welcome](https://github.com/mikemcquaid/GitHub-Markdown-Font-Settings.tmbundle/pulls).

## Contact
[Mike McQuaid](mailto:mike@mikemcquaid.com)

## License
GitHub-Markdown-Font-Settings.tmbundle is licensed under the [MIT License](http://en.wikipedia.org/wiki/MIT_License). The full license text is
available in
[LICENSE.txt](https://github.com/mikemcquaid/GitHub-Markdown-Font-Settings.tmbundle/blob/master/LICENSE.txt).
