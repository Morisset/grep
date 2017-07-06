# grep

    usage: grepcm [-h] [-A AFTER_CONTEXT] [-B BEFORE_CONTEXT] [-C CONTEXT] [-n]
                  [-c] [-r] [-v] [-V] [-l]
                  pattern file [file ...]

    positional arguments:
        pattern               pattern to search for.
        file                  file(s) to search in. Wildcards and directoies
                        accepted.

    optional arguments:
        -h, --help            show this help message and exit
        -A AFTER_CONTEXT, --after-context AFTER_CONTEXT
                        Print num lines of trailing context after each match.
                        See also the -B and -C options.
        -B BEFORE_CONTEXT, --before-context BEFORE_CONTEXT
                        Print num lines of leading context before each match.
                        See also the -A and -C options.
        -C CONTEXT, --context CONTEXT
                        Print num lines of trailing and leading context before
                        each match. See also the -A and -B options.
        -n, --line-number     Each output line is preceded by its relative line
                        number in the file, starting at line 1.
        -c, --count           Only a count of selected lines is written to standard
                        output.
        -r, --recursive       Recursively search subdirectories listed.
        -v, --invert-match    Selected lines are those not matching any of the
                        specified patterns. Used only with -l
        -V, --version         Display version information and exit.
        -l, --files-with-matches
                        Only the names of files containing selected lines are
                        written to standard output.
