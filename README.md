# Test input and output data for CMSC701 Assignment 0

The output `sars_cov2_sa_64.stat` in `test_output` was made by running `inspectsa` on the suffix array of the test genome with a sampling factor of `64`.

The output `sars_reads1.naive.map` in test_output was made by running the querysa on the suffix array of the test genome with the `test_input/reads1.fa` as input in `naive` mode, and the `simpaccel` and `prefaccel` variants were made in the corresponding way.
