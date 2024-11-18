# Knight Online Database Archive

This repository contains archived migration scripts from the [ko-db](https://github.com/ko4life-net/ko-db) project.

## Purpose

This repository was separated into a submodule to manage the growing size of archived migration scripts. A single, small migration script can generate a large `.diff` file, which would significantly increase the size of the main repository and slow down cloning over time.

By isolating these files into a dedicated submodule, we ensure that the main `ko-db` repository remains lightweight and quick to clone. This repository is optional and only required for those who wish to explore:

- Archived migration scripts.
- Corresponding `.diff` files.
- Historical development progress and changes made to the `ko-db` project over time.

## Usage

For every `ko-db` release, the archived migration scripts and their corresponding `.diff` files will be added here for reference.

To clone this repository as a submodule along with `ko-db`, use:

```bash
git clone --recurse-submodules https://github.com/ko4life-net/ko-db.git
```

If you have already cloned ko-db without submodules, you can initialize and update this repository using:
```bash
git submodule update --init --recursive
```
