# stopWatch
Uses closure to provide convenient, human readable references to the time of its instantiation and the time it was last called.

## Usage
`const checkWatch = require('stopWatch.js');`

`const time = checkWatch();`

`time.display.total === '0 ms'`

After ~30 seconds:

`time.display.total === '30 seconds'`

`time.display.lap === '30 seconds'`

After ~30 more seconds:

`time.display.total === '1.05 minutes'`

`time.display.lap === '31 seconds'`
