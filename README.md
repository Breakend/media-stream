Media-Stream
============

Setup:
  Run the install.sh script in devscripts

Run:
  Go in to the media-site directory and type meteor

Dependencies:
  For live transcoding you will need FFMpeg. 
  -For Windows you will need to manually download the exe and install it.
  -For Mac OsX, if you have a package manager like Homebrew, life will be much easier. Just brew install ffmpeg.
  -For Linux, use apt-get install ffmpeg

Tests:
  To run QUnit tests just open the related HTML file in the tests directory
