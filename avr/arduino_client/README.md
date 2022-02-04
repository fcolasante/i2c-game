# Arduino client
Draft for the synchronization between pc_client and arduino board.

## utils
**printf ()** is enabled for debugging, both for *stdout* and *stderr*

## Test
To test the synchronization, flash the `arduino_client.c` file on the arduino, via the `Makefile` (make sure the card is read on `/dev/ttyACM0`):
```s
$ make arduino_client.hex
```

Eventyally, launch **main**, from `/test UART/pc_server`.
