docker-check-deferred-deletion
==============================

Tests to see if your kernel supports deferred deletion

## Usage

### Run natively:
`sudo ./check_for_deferred_deletion.sh`

### Run in Docker:
`docker run -it --rm --cap-add SYS_ADMIN mbentley/check-deferred-deletion`
