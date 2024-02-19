
# Still

Still is a Python based static photo website generator that
- generates a pure HTML/CSS webpage giving an overview of your photos
- generates a page for each photo that allows you to click through to the next photo
- optionally resizes and copyrights your photos
- removes sensitive metadata (EXIF).

I developed Still to share my own photo-albums; for an example see: https://willemhekman.nl/albums.html

# Why

Most of us would like to share our photos with friends and family in a convenient way and rely on 3rd party services/social media to do so (eg Google Photos, Instagram). While these services work they abstract away many details and for example in some cases reduce the photo quality (Google Photos) --- if you want to share the original high resolution file you'll have to go through some tedious steps.

This static site generator can be used if you I just want to be able to share your (original or resized) photos via a plain website and was inspired by the work/website of Phil Greenspun.

# Quick Start

1. Put your photos into folders like you usually do --- each folder makes a photo album.
2. Clone this repo and put the static site generator script file just outside your photos directory.
3. Optionally set the constants in settings.py to set if/how to resize the photos.
3. Run the generator using "python still.py"
4. Now you will have the pure HTML pages returned in the html folder which you can then upload to your website eg via FTP.

still.py
photos/
├─ 20240608 - Greece/
├─ 20240701 - Italy/
html/

# Contribution

- Theming: It would be great to offer various CSS theme options. If you are into CSS it would be great if you could contribute more themes.
- Additional Features: If you can think of additional features, that would be great. Maybe a randon photo page?

# Credits

Thanks Philip Greenspun http://philip.greenspun.com/ for the original inspiration and inspiring articles on various topics.

