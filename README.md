docker-check-deferred-deletion
==============================

Tests to see if your kernel supports deferred deletion

## Usage

### Run natively:
`sudo ./check_for_deferred_deletion.sh`

### Run in Docker:
`docker run -it --rm --cap-add SYS_ADMIN mbentley/check-deferred-deletion`

If you receive an error like:
```
unshare: can't mount none on / (flags:0x44000): Permission denied
```
Run you will need to run:

`docker run -it --rm --privileged mbentley/check-deferred-deletion`
