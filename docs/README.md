## Advent Of Code Helper

Helper scripts for the [coding advent calendar](https://adventofcode.com) that assist with scraping, submitting, preparing day directories.

### Setup

I recommend symlinking configuration files (except `data/headers`), as they wont be tracked inside the submodule. An init script which symlinks config files into the submodule can be used to circumvent this.

1. Add this repository as a submodule to your aoc solutions git repository

2. Save the json request headers for accessing problem statements in `data/headers`

3. Ensure `data/config` points to a valid configuration file, use `data/sample-config` for reference

4. Run `source enable` from outside the submodule to enable the virtualenv and `aoc help` for a list of commands

5. (Optional) Symlink scripts for building and running a solution into `scripts` to run them via `aoc <cmd>`
