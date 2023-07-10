`cryo` is the easiest way to extract blockchain data to parquet, csv, or json

`cryo` is also extremely flexible, with [many different options](https://github.com/paradigmxyz/cryo#cli-options) to control how data is extracted + filtered + formatted

*`cryo` is an early WIP, please report bugs + feedback to the issue tracker*

*note that `cryo`'s default settings will slam a node too hard for use with 3rd party RPC providers. Instead, `--requests-per-second` and `--max-concurrent-requests` should be used to impose ratelimits. Such settings will be handled automatically in a future release*.