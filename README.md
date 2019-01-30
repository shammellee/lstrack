# lstrack

Track LaserShip packages from the command line

# Dependencies

* [cURL](https://curl.haxx.se/)
* [jq](https://stedolan.github.io/jq/)


# Usage

```sh
$ ./lstrack <tracking_id>
$ ./lstrack LX12345678

Order has been delivered
```

# TODO

* Display event history
* Add error handling
* Add signature + location details (eg, signed by John Doe, left at lobby)
* Tracking ID aliases (eg, "Dog food" instead of LX1234567)
* Read tracking IDs from file

