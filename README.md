## what is this?

**dezip** is a website for browsing source code archives.

to use it, type `dezip.org/` in your address bar, then the address of the archive file, like this:

[`dezip.org/https://www.lua.org/ftp/lua-5.4.2.tar.gz`](https://dezip.org/https://www.lua.org/ftp/lua-5.4.2.tar.gz)

## what motivated you to make it?

discomfort with the centralization of software development into sites like github and gitlab.  convenient source code browsing shouldn't be coupled so tightly to repository hosting services.

## which protocols and archive formats are supported?

currently, the following protocols are supported: `http://`, and `https://`; and the following archive formats, identified by file extension: `.zip`, `.tgz`, `.tar.gz`, `.tb2`, `.tbz`, `.tbz2`, `.tar.bz2`, `.txz`, and `.tar.xz`.

## is there a way to search?

yeah!  click the **magnifying glass button** or press **f** to bring up the search field.  selected text will appear in the field automatically (so you don't have to copy and paste it).  press enter to search.  **j** and **k** move forward and backward through search results.

## where can i find the source code?

the latest release is available [here](https://github.com/jasonrdsouza/dezip/releases), or you can [browse the code on github](https://github.com/jasonrdsouza/dezip) (until we start self hosting).

see [BUILD.md](BUILD.md) for build instructions.

## who made this?

dezip was originally made by **ian henderson**, and this fork is maintained by **jason dsouza**

## todo

- Add support for uncompressed files
- Add more logging output
- Add support for navigating to a specific line in a file
- Add darkmode support

## developing

- since pages get pre-rendered, if you change something about the page, make sure to clear out the cache on disk in order to see your changes

