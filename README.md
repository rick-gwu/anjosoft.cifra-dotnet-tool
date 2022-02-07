# Cifra

v.1.0.0

This is the dotnet tool version of Cifra &#169;


This app provides real-time encryption/decryption of plain text.<br />
You may provide a secret key (password) or use a randomly generated one.<br />
Be sure to remember the secret key or to keep it in a safe place.<br />



You may encrypt plain text by typing, copying and pasting, or by providing the path to a file stored in your local device.



Cipher text and secret key will be displayed once encryption/decryption is complete.<br />
You will have the option to save the result to the local file system if desired.



### Installation

Download the [latest version of Cifra](https://github.com/rick-gwu/anjosoft.cifra-dotnet-tool/releases/latest)<br />
In Terminal (or Command-line in Windows), enter: ``dotnet tool install --global --add-source <source_folder> anjosoft.cifra``

For example, if your terminal session is pointing to the Home directory and you downloaded **anjosoft.cifra.1.0.0.nupkg** to your **Downloads** folder, run:  ``dotnet tool install --global --add-source ./Downloads anjosoft.cifra``

If you are getting a 401 error when installing the tool on Windows, you may try using the **ignore-failed-sources** flag: ``dotnet tool install -g --add-source ./Downloads --ignore-failed-sources anjosoft.cifra``

To start using the tool, simply type **cifra** at the prompt.<br />
To uninstall the tool, run ``dotnet tool uninstall -g anjosoft.cifra``<br />

For more information and other installation options, see Microsoft's article on [how to manage .NET tools](https://docs.microsoft.com/en-us/dotnet/core/tools/global-tools)

For help with installation errors, see Microsoft's article on [how to troubleshoot .NET tool usage issues](https://docs.microsoft.com/en-us/dotnet/core/tools/troubleshoot-usage-issues)
