python-bitcoinrpc is an improved version of python-jsonrpc.

It includes the following generic improvements:

* HTTP connections persist for the life of the `ServiceProxy` object
* sends protocol `version` via JSON-RPC 1.1
* sends proper, incrementing `id`
* uses `json` of the Python Standard Library

It also includes the following Bitcoin-specific details:

* sends Basic HTTP authentication headers
* parses all JSON numbers that look like floats as `Decimal`
