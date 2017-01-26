# vision-databases
A repository of starter databases for your Vision system.

To download a database, select a database (for example _investNet_) from the __Branch__
dropdown in the upper left corner of this repository's home page, choose __Download ZIP__
from __Clone or Download__, and unpack the downloaded ZIP file into a directory of your choosing.

If you prefer, you can also use _git_ directly to clone this repository and check out the
branch whose name matches the database you want.

Once the database you selected is in a directory on your machine, open it using the
_-n path-to-database-NDF_ option of either _batchvision_, Vision's command line interpreter, or
_vision_, Vision's text based graphical  editor.  For example, if you downloaded the _investNet_
database into the _mydatabases_ subdirectory of your home directory, you can type:

    _batchvision -n ~/mydatabases/investNet/NDF_

or:

    _vision -n ~/mydatabases/investNet/NDF_

You can also set the _NDFPathName_ environment variable to point to the location of your database's _NDF_ file:

    _export NDFPathName=~/mydatabases/investNet/NDF_

so that you do not have to pass the _-n_ option every time you want to use your database:

    _vision_
