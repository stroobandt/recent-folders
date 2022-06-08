DESCRIPTION

    Opens a list of recently used folders on the desktop.
    The chosen folder is opened with the default file manager.


USAGE

    $ recent-folders


REQUIRES

    System package zenity is usually preinstalled with the desktop
    environment, if not:

        $ sudo apt install zenity

    Automatically installed from PyPI: lxml, pandas, screeninfo


COPYRIGHT

    Copyright (C) 2012-2022 Serge Y. Stroobandt
    Copyright (C) 2014      Martin Hansen

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses/>.


CONTACT

    echo c2VyZ2VAc3Ryb29iYW5kdC5jb20K |base64 -d


TODO

    - Implement module xdg.RecentFiles for desktop environments
      complying with XDG Recent File Spec 0.2.
