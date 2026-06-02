# HAKAMIQ

I'm working on small tools for checking, organizing, and inspecting local game files.

One of the ideas I'm working on is a PS3 local content verifier. The tool is meant to help users check files they already have on their own device by comparing file size and checksums with a database they provide themselves.

The idea is simple:

- import a local database
- scan local PS3 files or folders
- calculate MD5, SHA1, and SHA256
- compare the result with the imported database
- show whether the file is verified, mismatched, unknown, or unsupported

This project is not a downloader and does not include game files, licenses, keys, or download links.

Users are responsible for their own files and databases.
