# vision-databases
You have selected the __investNet__ database.

---

To download this database now, choose __Download ZIP__ from the __Clone or Download__ dropdown
above and unpack the downloaded ZIP file into a directory of your choosing.

If you prefer, you can also use _git_ directly to clone this repository and check out its
_investNet_ branch.

Once the _investNet_ database is on your computer, open it using the _-n_ option of either
_batchvision_, Vision's command line interpreter, or _vision_, Vision's text based graphical
editor.  If, for example, you downloaded the _investNet_ database into the _mydatabases_
subdirectory of your home directory, run:

    batchvision -n ~/mydatabases/investNet/NDF

or:

    vision -n ~/mydatabases/investNet/NDF

You can also set the _NDFPathName_ environment variable to point to the location of _investNet_'s
_NDF_ file:

    export NDFPathName=~/mydatabases/investNet/NDF

so that you do not have to pass the _-n_ option every time you want to open this database:

    vision
