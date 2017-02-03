# WiX Extended Bootstrapper Application

> An extended WiX bootstrapper Application based on the WiX standard bootstrapper application.

## Features

This version has the following enhancements over the standard code:

* Resized HyperlinkLicense and RtfLicense so they are the same size as the default WiX UI – this is useful if you need to show an MSI internal UI.
* Add welcome message to HyperlinkLicense install page.
* Add support for Radio buttons on the option and install pages.
* Add support for checkboxes on the install page (they are already supported on the options page).
* Add support for second directory folder on the option page.
* Add Hyperlink2Theme theme (and example) that supports a larger logo on the install page (see images below).
* Add example textbox on the options page (this is part of the standard BA but not documented).
* Added install version number to HyperlinkLicense install page.
* Reformat the RtfLicense to have flat licence textbox.
* Add preprocessor instruction to create an auto increment version (like the C# AssemblyInfo format 1.0.*)
* Support for Bundle self-updates
* Support for external functions in the extension UI.
* Support for disabling controls based on conditions.

## License

Copyright (c) 2004, Outercurve Foundation.  
This software is released under the Microsoft Reciprocal License (MS-RL)
