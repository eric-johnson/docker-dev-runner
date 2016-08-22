# Docker Dev Runner

Docker Dev Runner is:
- Such a boring name.
- Useful if you don't want to install your code's dependencies directly on your machine.
- A tool at runs commands in a docker container that you specify. It climbs your `$PWD` looking for a `.docker-image` file and it runs that container with the command you specify.

## Example
```
# ln -s /path/to/docker-dev-runner/bin/drun /usr/local/bin/drun

$ cd my-project
$ echo "ruby" > .docker-image
$ drun irb

irb(main):001:0>
```
