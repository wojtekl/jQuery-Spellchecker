# jQuery-Spellchecker
spell check plugin for CKEditor

## SCREENSHOTS
![Preview](/preview.png)

## AUTOHRS
- [Richard Willis](https://github.com/badsyntax/jquery-spellchecker),
- [wojtekel](http://mojemiejsce-wojtekel.rhcloud.com).

## CONFIGURATION
jqueryspellchecker/plugin.js
- replace 'pl' with desired language code where 'lang'.

## INSTALLATION
1. Download CKEditor with WebSpellChecker plugin.
2. Install aspell.
3. Install php-enchant or php-pspell and libpspell-dev.
4. In jqueryspellchecker/plugin.js:
- replace 'enchant' with 'pspell' where 'driver' if installed second one or skip this step otherwise.
5. Move jqueryspellchecker directory to CKEditors plugin directory.
6. Move css, js and webservices directories to CKEditors directory.
7. Append 'jqueryspellchecker' to 'extraPlugins'.
