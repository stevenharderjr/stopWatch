# stopWatch
Uses closure to provide convenient references to the time of its instantiation and the time it was last called.

## Usage
`const checkWatch = require('stopWatch.js');`

`const time = checkWatch();`

`console.log(time.display.total); // '0 ms'`

... wait ~30 seconds ...

`console.log(time.display.total); // '30.1 seconds'`
`console.log(time.display.lap);    // '30.1 seconds'`

... wait ~30 more seconds ...

`console.log(time.display.total); // '1.05 minutes'`
`console.log(time.display.lap);    // '31 seconds'`
