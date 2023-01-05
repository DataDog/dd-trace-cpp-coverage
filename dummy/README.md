This is a dummy directory that continuous integration jobs can target in a
sparse checkout of this branch.  This way, a directory (new coverage report)
can be added to the branch without having to first fetch all previous coverage
reports.  See [publish-coverage][1] in the `dd-trace-cpp` repository.

[1]: https://github.com/DataDog/dd-trace-cpp/blob/main/bin/publish-coverage
