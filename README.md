# LinVST-Linker
Useful scripts to create links for LinVST bridging software

### Usage: w2lvst2 and w2lvst3 (Create a Linux VST bridge for Windows VST's).
To use the w2lvst2 script type ./w2lvst2 and give the absolute path to the directory where .dll plugins are stored. If it finds your VSTs it will create a $HOME/.vst/windows-bridged/ directory with your VSTs by default.
To use the w2lvst3 script type ./w2lvst3 and give the absolute path to the directory where .vst3 plugins are stored. If it finds your VSTs it will create a $HOME/.vst3/windows-bridged/ directory with your VSTs by default.
You can also install these scripts globally by putting them in /usr/local/bin or /usr/bin.
If installed globally, then you can run these scripts from the directory where the .dll and .vst3 plugins are stored.
These scripts work with Nautilus and other file managers that use file actions. For use with Nautilus put these files in the $HOME/.local/share/nautilus/scripts directory.
