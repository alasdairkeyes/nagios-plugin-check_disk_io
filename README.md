# nagios-plugin-check_disk_io
Nagios plugin to report disk IO


Dependencies
- iostat binary from the sysstat package


Installation
- Copy the check_disk_io to your nagios plugin folder and set executable
- Add a line to your nrpe.cfg file
command[check_disk_io]=@libexecdir@/check_disk_io/check_disk_io -c 80 -w 70 -s 5 -d sda

Examples
- Run with the -h argument to see further examples

Author
- Alasdair Keyes - https://akeyes.co.uk/


License
- Released under GPL V2 
  http://www.gnu.org/licenses/old-licenses/gpl-2.0.html
  See included LICENSE file
