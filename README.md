## Installing

1. Quit Emacs.
2. Delete `~/.emacs.d` (and/or `~/.emacs`) if it exists.

   This is where Emacs looks for configuration files, and deleting these files and directories will ensure that you start with a clean slate.

   (Windows users, your Emacs files will probably live in `C:\Users\<USER_NAME>\AppData\Roaming\`. So, for example, you would delete `C:\Users\<USER_NAME>\AppData\Roaming\.emacs.d`.)
3. git clone the Emacs [configuration](https://github.com/finalfantasia/emacs-for-clojure) into `~/.emacs.d`:

   `git clone https://github.com/finalfantasia/emacs-for-clojure ~/.emacs.d`
4. Launch Emacs.

   It should start installing packages. Note that compilation of some packages might cause warnings which, most probably can be ignored.

## Organization

I've tried to separate everything logically and document the purpose of every line. [`init.el`](./init.el) acts as a kind of table of contents.  It's a good idea to eventually go through `init.el` and the files under the `customizations` directory so that you know exactly what's going on.
