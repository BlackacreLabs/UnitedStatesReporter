# The United States Reporter

Opinions of the United States Supreme Court

## Data Formats

Opinion texts are stored in [Precedent][Precedent] format, a lightweight
markup language that is easily translated to JSON, YAML, or your
preferred structured interchange format. Case metadata is stored in
[YAML][YAML] format.

Both formats are readable by programmers and non-geeks alike. Even if
you've never looked at source code or computer data files before, you
should have no trouble figuring them out.

[Precedent]: https://github.com/BlackacreLabs/precedent

[YAML]: http://www.yaml.org

## Using the Data

Unless you are interested in contributing large changes or additions to
the dataset, you should probably [download a ZIP archive][ZIP] of the
most recent versions of all files and work with those.

[ZIP]: https://github.com/BlackacreLabs/UnitedStatesReporter/archive/master.zip

Those interested in contributing should note that the repository
includes many files in many nested directories. Git is not optimized for
such uses. The working tree takes up a lot of space and may make Git far
less responsive than usual, especially on machines with slow mechanical
disk drives. On the other hand, the repetitiveness of the plain text
facilitates effective compression for local repository storage and
network transfers. If any of this poses problems, feel free to use
GitHub's web-based editor.
