# FreeFem++ Syntax for Sublime Text 3

This is a very simple syntax highlighting for FreeFem++ in SublimeText 3. I cannot guarantee this would work with your version.

You should only need to copy the file "FreeFem++.tmLanguage" directly into your "Sublime Text 3/Packages" folder.

For example on OSX El Capitan this would be:
/Users/<username>/Library/Application Support/Sublime Text 3/Packages/FreeFem++

Sublime should detect automatically the new package and create a syntax highlight with the name "FreeFem++".

The "FreeFem++.YAML-tmLanguage" is the "source file" which is compiled by the package "AAAPackageDev" into the "FreeFem++.tmLanguage" file which is used by sublime for the definition of the syntax. You can modify anything you want on the YAML file and re-compile it if you want to make improvements.
