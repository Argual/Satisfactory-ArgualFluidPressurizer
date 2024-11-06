
# Localization Guide  

These are the exported localization files. The `.po` files are the raw exports, and the `.json` files are processed by me into a format that contains only the relevant information and is better suited for some automation tools and for AI translation.

To request a translation, please open a new issue that contains the following information:  
- The language you translated.
- The translations (Either a `po` or `json` file.) If you are translating a new language, make sure the translations are all there.
- Optional: The name and/or link to your profile you would like to be credited as.

You can also issue corrections for existing translations. When you are correcting translations, please only submit a file that contains only the corrected entries.

## Json

The `json` translations need to contain a `"Key"` and a `"Value"` for each entry. The `"Key"` must be unchanged, the `"Value"` must be the translated value. The `"Id"` is only for informational purposes. The `json` cannot contain comments.

## Po

The po translations need to contain a `msgctxt` that is the unchanged key of the entry, followed by the `msgid`, which is the unchanged message id, followed by `msgstr`, wich is the translated value. Entries (one entry is these 3 lines) must be separated by at least 1 empty line. The lines starting with `#` are comments, and will be ignored.

## Please read this

Please check your uploads for errors. When you upload a file with syntax errors or missing translations, I <strong>may</strong> correct them and finish the translations, but I also may just reply with "there was some error in the translation". Depends on the free time I have at the time I look at your issue.
