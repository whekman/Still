
# Still

Still is a Python based static photo website generator that builds a pure HTML/CSS based hierarchical overview of your photos, optimally resizes and copyrights your photos, and removes sensitive metadata (EXIF).

For an example see: https://willemhekman.nl/albums.html

# Why

Most of us would like to share our photos with friends and family in a convenient way and rely on 3rd party services/social media to do so (eg Google Photos, Instagram). While these services work they abstract away many details and for example in some cases reduce the photo quality (Google Photos) --- if you want to share the original high resolution file you'll have to go through some tedious steps.

This static site generator can be used if you I just want to be able to share your (original or resized) photos via a plain website and was inspired by the work/website of Phil Greenspun.

Basically, you put your photos into folders --- each folder makes a photo album --- then you run the generator script to have returned pure HTML pages that render your photo albums.

Working Directory:

photos/
├─ 20240608 - Greece/
├─ 20240701 - Italy/
still.py
html/

# Quick Start

Clone the repo and place your photo albums in the appropriate folder. Then follow the instructions in the main Jupyter Notebook to set the global variables needed to resize and copyright your photos. Run the main function to generate your hierachical website section.

# Contribution

- Theming: It would be great to offer various CSS theme options. If you are into CSS it would be great if you could contribute more themes.
- Additional Features: If you can think of additional features, that would be great. Maybe a randon photo page?

# Credits

Thanks Philip Greenspun for the original inspiration for this project and his inspiring articles on various topics.

