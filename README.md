# php-extensions
## Compiled PHP extensions.

### Windows
1. Put the extension in the extensions folder under PHP's install path.

2. Edit php.ini to load the extension.
    1. Find `; Dynamic Extensions ;`
    2. Add line `extension=myextension.dll`
3. Restart webserver
