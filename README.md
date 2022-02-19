# kiss-libdemi

kiss packages with libdemi support (experimental alternative to libudev)

## Usage

```sh
# clone repo
git clone https://github.com/illiliti/kiss-libdemi

# add repo to KISS_PATH
export KISS_PATH="$PWD/kiss-libdemi:$KISS_PATH"

# remove libudev-zero
KISS_FORCE=1 kiss r libudev-zero

# build stuff
kiss b libdemi libinput wlroots sway
```
