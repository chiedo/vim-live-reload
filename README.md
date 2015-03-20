**Vim-live-reload**  -  Automatically reload the current file when it changes
==================================
When running, the current file will automatically update whenever it's contents are changed.

This is not original work. It has been brought over from work by David Fishburn and Tyler Rick with minor modifications. 

Installation
------------------------
### Pathogen Install
1. Navigate to your **[VIM_ROOT]/bundle** directory in your local Vim setup
2. git clone https://github.com/chiedojohn/vim-live-reload.git


Usage
-------------------------
To start live reload for the current file, run the following:
```
:LiveReload
```

To start live reload for all current files:
```
:LiveReloadAll
```

To start live reload only for the current buffer:
```
:LiveReloadWhileInThisBuffer
```

To stop live reload, just run the same command that you used to start it. The commands toggle the functionality on and off.

With any of the commands above, add a bang (!) after the command (eg. LiveReload!) to make the file auto update without first prompting you.

License
------------------------------------------------------
Distributed under the same terms as Vim itself. See :help license.

Credits
-----------------------------------------------------
David Fishburn and Tyler Rick - http://vim.wikia.com/wiki/Have_Vim_check_automatically_if_the_file_has_changed_externally
