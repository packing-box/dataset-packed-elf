# Dataset of packed ELF files

This dataset was made from a set of 482 not packed cleanware including executable and object files coming from `/usr/bin` from a fresh installation of Ubuntu 20.04. From this folder of not packed binaries, we built the 6 subsets with the packers integrated in the [Packing Box](https://github.com/packing-box/docker-packing-box) with the `dataset make` command, using the `--pack-all` option. We end up with 200 binaries randomly chosen from the not packed folder per packer. This dataset can be used for training machine learning models tailored to ELF executable packing.


## :star: Related Projects

You may also like these:

- [Awesome Executable Packing](https://github.com/packing-box/awesome-executable-packing): A curated list of awesome resources related to executable packing.
- [Bintropy](https://github.com/packing-box/bintropy): Analysis tool for estimating the likelihood that a binary contains compressed or encrypted bytes.
- [Dataset of packed PE files](https://github.com/packing-box/dataset-packed-pe): Dataset of PE samples packed with many different packers.
- [Docker Packing Box](https://github.com/packing-box/docker-packing-box): Docker image gathering packers and tools for making datasets of packed executables.
- [PEiD](https://github.com/packing-box/peid): Python implementation of the Packed Executable iDentifier (PEiD).
- [PyPackerDetect](https://github.com/packing-box/PyPackerDetect): Packing detection tool for PE files.

<!--Example of visualization created with [Bintropy](https://github.com/packing-box/bintropy):

<p align="center"><img src="https://raw.githubusercontent.com/packing-box/docker-packing-box/main/docs/imgs/calc.png"></p>-->

