# Fix Random Number Generator

It generates fix random number for a fixed input string. Random numbers which will be generated based on fix string.

## Usage

#### Import the script

import the script in the head section of the file
<script src="fix-random.min.js"></script>

#### Method call

fixRandom(fixString, numberOfRandomNumber);

1. fixString - fixed string based on which random numbers will be generated
2. numberOfRandomNumber - no of random number to be generated, no more than 32

The method returns an array of random number fix for the given string, i.e. if same string is inputted it generates the same random number.

## Dependency

Thanks to dchest's [github repo](https://github.com/dchest/fast-sha256-js)

