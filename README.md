
# headcat

  Useful for grepping csvs while retaining the header

## Installation

  Install with [ghi](https://github.com/stephenmathieson/ghi)

    $ ghi install jb55/headcat

  Install with git+make

    $ git clone https://github.com/jb55/headcat /tmp/headcat && cd /tmp/headcat && make install

## Example

    $ <file.csv grep "Thing" | headcat file.csv > newfile.csv

## Usage

    headcat <headerfile> [files...]

## License

  GPLv2
  
    headcat - cat the head of a file with other files
    Copyright (C) 2015  William Casarin

    This program is free software; you can redistribute it and/or
    modify it under the terms of the GNU General Public License
    as published by the Free Software Foundation; either version 2
    of the License, or (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License along
    with this program; if not, write to the Free Software Foundation, Inc., 51
    Franklin Street, Fifth Floor, Boston, MA  02110-1301, USA.
