# All Pairs Shortest Paths

The APSP algorithm is also a pathway reconstruction algorithm that connects every source to every target, returning the induced edge subnetwork from these paths.

## Usage

```
usage: allpairs.py [-h] --network NETWORK --nodes NODES --output OUTPUT [--directed | --no-directed]
allpairs.py: error: the following arguments are required: --network, --nodes, --output
```

Where:
- `network` is a weighted `tsv` edgelist (`source`, `target`, `weight`)
- `nodes` is a no-header tsv of node names and their type (`source`/`target`)
- `output` is the place to output the subnetwork
- `--directed/--no-directed` specifies whether the interactome is fully undirected or fully directed.
