# MarmosetSubmit
A script for submitting file to Marmoset Server in University of Waterloo

## Examples
Submit a single file
```bash
marmoset_submit -q [questid] -c [course] -p [project] [file]
```
Submit a zip package
```bash
marmoset_submit -q [questid] -c [course] -p [project] -z [files..]
```
Adding -s can save current configuration
```bash
marmoset_submit -s -q [questid] -c [course] -p [project] [file]
marmoset_submit -s -q [questid] -c [course] -p [project] -z [files..]
```
Auto-submit based the confugration file
```bash
marmoset_submit -a
```

## Example
```bash
./marmoset yourid cs241 a1p1 test.cc
```

## Suggestion
This script submits your file through Student Computing Environment, so it may require your password for multiple times. It is recommended to set up your ssh key.

For more information about ssh key: [Generating SSH keys](https://help.github.com/articles/generating-ssh-keys/)
