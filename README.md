# pykdclient

Basic tool to print out XBOX (original) debug messages sent via the KD protocol.

## Usage

1. Start up windpl.py in server mode, listening on an arbitrary port:
   `windpl.py --serve --port 9091`
1. Run `xemu` or `xqemu` with serial port enabled and pointing at the
   `pykdclient`. E.g., with the command-line args:
   `-device lpc47m157 -serial tcp:127.0.0.1:9091`
