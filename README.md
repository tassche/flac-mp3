flac_mp3.py
-----------

Script to convert FLAC to MP3 using [FFmpeg][1].

[1]: https://www.ffmpeg.org/


#### Requirements

* Python 3.4
* FFmpeg (make sure the ffmpeg executable is in your PATH)


#### Usage

    $ python3 flac_mp3.py -h
    usage: flac_mp3.py [-h] [-r] SOURCE [SOURCE ...] TARGET

    positional arguments:
    SOURCE      file or directory to convert
    TARGET      target directory for the converted files and/or directories

    optional arguments:
    -h, --help  show this help message and exit
    -r          search subdirectories
