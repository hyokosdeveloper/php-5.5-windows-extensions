- Extract `ImageMagick-6.8.6-8-Q16.7z` to `C:\ImageMagick-6.8.6-8-Q16`
- Add `C:\ImageMagick-6.8.6-8-Q16` to `Path` environment variable
- Set new environment variable `MAGICK_HOME` to `C:\ImageMagick-6.8.6-8-Q16`
- Enable imagick extension by editing your `php.ini` by appending `extension=php_imagick.dll`
- Restart
- Profit

Of course it is possible to install IMagick to a directory of your choice, just update the environment variables accordingly and restart.
