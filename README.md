## Work in progress docker-compose environment for freeems

Currently contains docker build for the freeems toolchain. Work in progress for
FreeEMS-Loader and various other tools.

### Requirements
 * docker
 * docker-compose

### Usage
 * create .env with `FREEEMS_PATH=/my/path/to/freeems/source`
 * to build firmware:
   ```
   docker-compose run freeems-toolchain make BENCHTEST
   ```
