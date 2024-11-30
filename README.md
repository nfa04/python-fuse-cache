# Fuse Cache

Fuse Cache is a simple FUSE filesystem for caching files from a remote filesystem on a local filesystem for faster access while always remaining in sync. It also features a queue to reduce strain on upload bandwith.

## Credits
Credits to Stavros Korokithakis (@skorokithakis) for the base passthrough sample which I extended. See: https://github.com/skorokithakis/python-fuse-sample