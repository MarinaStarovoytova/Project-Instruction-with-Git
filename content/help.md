[//]: # ( помощь git )

[< Назад](/readme.md)

# Помощь при использовании Git

При использовании Git, есть три способа открыть страницу руководства по любой команде Git:

    git help <команда> 

    git <команда> --help

    man git-<команда>

Например, так можно открыть руководство по команде `git config`

    git help config

Эти команды хороши тем, что ими можно пользоваться всегда, даже без подключения к сети.

Так же, если вам нужно посмотреть только список опций, можно использовать опцию `-h` для вывода краткой инструкции по использованию:

    git add -h

    usage: git add [<options>] [--] <pathspec>...

    -n, --dry-run         dry run
    -v, --verbose         be verbose

    -i, --interactive     interactive picking
    -p, --patch           select hunks interactively
    -e, --edit            edit current diff and apply
    -f, --force           allow adding otherwise ignored files
    -u, --update          update tracked files
    --renormalize         renormalize EOL of tracked files (implies -u)
    -N, --intent-to-add   record only the fact that the path will be added later
    -A, --all             add changes from all tracked and untracked files
    --ignore-removal      ignore paths removed in the working tree (same as --no-all)
    --refresh             don't add, only refresh the index
    --ignore-errors       just skip files which cannot be added because of errors
    --ignore-missing      check if - even missing - files are ignored in dry run
    --sparse              allow updating entries outside of the sparse-checkout cone
    --chmod (+|-)x        override the executable bit of the listed files
    --pathspec-from-file <file>
                          read pathspec from file
    --pathspec-file-nul   with --pathspec-from-file, pathspec elements are separated with NUL character
