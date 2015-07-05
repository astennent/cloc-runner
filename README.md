# cloc-runner
Adds a right-click option to Windows Explorer to run the cloc (Count Lines of Code) command line tool.

## Manual Installation
1. Download this repository as a zip file and extract the contents to "C:\Program Files\cloc" so that the file structure looks like "C:\Program Files\cloc\cloc-runner.bat" etc.
2. From that folder, run "cloc-reg.reg" by double-clicking it to add the registry keys.
3. That's it! Now right clicking any folder or file in Windows Explorer will have an option "Count Lines of Code" which will execute run the command line tool.

*Note*:  If you want to manually update the version of cloc, or change the location of your executable file (if, for example, you do not have admin access), make sure you edit "cloc-reg.reg" to reflect the changes.

## Automatic Installation
  * Not set up yet. 

## Updates
  * Also not set up yet.

## Compatibility
  * Requres Windows Vista or higher

## License
  * cloc is licensed under the [GNU General Public License, v2](www.gnu.org/licenses/gpl-2.0.html). 
  * I did not write cloc. This wrapper is licensed under the [MIT License](http://opensource.org/licenses/MIT). I don't care what you do with it. If you write something that I didn't think of then feel free to contribute.
