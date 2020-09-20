# kiss-aosync

My personal repositories of kiss packages. This repository depends on the Community repo.

## chromium

The Portable Linux musl binary package of ungoogled-chromium has been packaged as `ungoogled-chromium-bin`!  
And thanks to Dylan's (libdbus-stub)[https://github.com/dylanaraps/libdbus-stub], it is now DBus free!

You can now enjoy a native chromium experience on your favorite distro and your beloved libc. You may encounter sandbox errors on some sites, making the tab crash. If that happens, simply run chromium with the `--no-sandbox` flag. If you are annoyed by the warning that says --no-sandbox is not supported, append the `--test-type` flag to silence that error.

## EXPERIMENTAL

Even if some packages here work, I do not yet endorse the use of this repo to the public. The packages suffixed with `-exp` are experimental and **won't work**.  

This includes notably `ungoogled-chromium-exp`.
