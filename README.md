# fontset

Curated list of fonts - CJK version.

All fonts should contain their origin and corresponding license, and should be free to for commercial use.



## Repo Structure

 * Additionally, fonts are categorized into different sub-directory by their type / source.
 * all fonts are placed in their separated folder along with necessary information ( license, source, referrer, etc )
   - fonts can be put together in the same folder if they share the same license and source information.
 * there should be a metadata file in each subfolder to describe the information of fonts.
   - metadata file could be in .pb or .json format, or any other formats that are parse-able by JS.
   - when metatdata is absent, font file should be named after following rule:
       - `<font-name>.<ext>`
       - `<font-name>-<variant>.<ext>`

 * fonts from other repo are included with git submodule.


## License

All fonts listed here should be released under open license that are okay for redistribution and commercial use, including but not limited to:
 * SIL Open Font License
 * Apache License
 * GPL
 * Ubuntu Font License

Detail of corresponding license for each font should be available in the directory for that font.

Source code except those from fonts repo are released under MIT License.
