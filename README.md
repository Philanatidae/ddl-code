# ddl-code
Basic syntax highlighting for the Open Data Description (OpenDDL) language.

## Known Issues
Syntax highlighting provided by this extension is compatible with Version 3.0 of the OpenDLL specification with the following exceptions:

 - Base64 data does not highlight properly. Since there is no prefix (`0x`, `0b`, etc.), it is impossible to distinguish from either identifiers or comments. This could be changed in the future by providing a more aware grammar definition or with a language server.

## License
This extension is released under the MIT license. See `LICENSE` for more info.

## Releases
### V1.0.0
Initial release. Support for OpenDDL 3.0 files except for Base64 data.
