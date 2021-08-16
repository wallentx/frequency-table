# frequency-table
I wanted to be able to easily see how many cores were reaching their turbo frequencies.
The problem with using `watch grep \"cpu MHz\" /proc/cpuinfo` is that it isn't easy to see that info, and for systems with lots of cores, the info wouldn't even fit in the terminal.

![ftable](/ftable.png)

## Usage
`ftable [options]`

### Options
```
  -m <1000-9999>	highlight frequencies above threshold
  -n <SECS>			seconds to wait between updates (Default: 2)
```
