# AlphaFold

This is RCC's modified version of [AlphaFold](https://github.com/deepmind/alphafold).

## Changes

Parallel running of MSA tools (From [fuji8](https://github.com/fuji8/alphafold/tree/msa-concurrent))

Unlocked CPU limits for jackhmmer, hhblits, and hmmsearch.

Script to run AF2 "without docker" (from [kalininalab](https://github.com/kalininalab/alphafold_non_docker))

Modified Dockerfile to take in inputs from environment variables for Kubernetes.
