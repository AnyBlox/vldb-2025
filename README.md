# AnyBlox VLDB 2025 artifacts

This repository contains artifacts for the *AnyBlox: A Framework for Self-Decoding Datasets* paper submitted for VLDB 2025.

*IMPORANT*: This repository heavily utilizes submodules. Make sure you clone it with `git clone --recurse-submodules`,
or later run `git submodule update --init --recursive`.

## Organization

The main code of the AnyBlox framework is located in the `anyblox` directory.

Each of the the three systems we integrated AnyBlox into have their separate directory.
Consult their README files for information specific to a given integration.

## Datasets

Data used in the paper can be downloaded with the `anyblox/dataset-download.sh` script.
See the script contents for source URLs.
