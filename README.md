# git-file-creators

Small Python2 script that lists files in GIT along with the author who created each file.

Pass --show-deleted to include files that no longer exists in the working directory
(typically because they were deleted in some pre-HEAD revision).

## Usage

```shell
# Run in the root of a git repo to list all files along with author who added them.
$ git-file-creators

# Same as above but only for files inside "foo" directory.
$ cd foo
$ git-file-creators -- .

# Same as above but also show deleted files.
$ git-file-creators --show-deleted -- .
```

## License

MIT
