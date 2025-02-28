# 3ds test for now

more to come later

## Installation

1. build binary (eventually will be in the releases section)
2. transfer binary to 3ds SD card
   - I'd recommend ftp but you can move it to the SD card manually as well
3. use homebrew launcher to launch it

## Building

1. install docker
2. obtain docker image for devprokit
3. `docker compose up -d`
4. `docker exec -it devkitarm_container bash`
5. `make`
