# stopWatch
Uses closure to provide convenient references to the time of its instantiation and the time it was last called.

## Usage
`const checkWatch = require('stopWatch.js');`

`const time = checkWatch();`

`console.log(time.display.total); // '0 ms'`

After ~30 seconds:

`console.log(time.display.total); // '30 seconds'`

`console.log(time.display.lap);    // '30 seconds'`

After ~30 more seconds:

`console.log(time.display.total); // '1.05 minutes'`

`console.log(time.display.lap);    // '31 seconds'`
