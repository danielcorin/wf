wf
===
Bash utility to toggle Airport Wi-Fi. Provides quick interface for resetting wireless internet connection.

## Usage
`wf [-on | -off | -d | -h]`

## Examples
Toggle WiFi (off, then on)

	$ wf
	WiFi reset
	
Toggle WiFi with 2 second delay

	$ wf -d 2
	WiFi reset
	
Turn WiFi off

	$wf -off
	WiFi off
	
## Options
	  -on
	      Turns Wi-Fi on.
	  -off
	      Turns Wi-Fi off.
	  -d | --delay | -delay [delay_length]
	      Turns Wi-Fi off, waits 'delay_length' seconds, then turns Wi-Fi on.
	      If not supplied, delay_length is 1 second.
	  -h | --help | -help
	      Displays script help.
	

## License
The MIT License (MIT)

Copyright (c) 2014 Daniel Corin

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.


## Credits

Pieces of code borrowed from

* [todo.txt](http://todotxt.com/) (for help display)
* [DGKApps](http://www.dgkapps.com/blog/osx-tips/osx-tips-turn-off-wifi-from-the-command-line/)
