## Usage

tasklist shows "TODO, FIXME, etc." comments in files.

Default patterns are `*.c` `*.h` `*.S`

Default exclude is `./git`

```
usage: tasklist [-h] [-n] [-p PATTERN] [-e EXCLUDE] [-t] [-s] [-v] [dir]

positional arguments:
  dir                   Specify search directory

optional arguments:
  -h, --help            show this help message and exit
  -n, --no-colors       Disable ANSI-Color-Sequences
  -p PATTERN, --pattern PATTERN
                        Search pattern
  -e EXCLUDE, --exclude EXCLUDE
                        Exclude directories
  -t, --total           Enable overall stats
  -s, --summary         Just give me a list of tasks
  -v, --verbose         Increase verbosity
```
