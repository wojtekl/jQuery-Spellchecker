# jQuery-Spellchecker
spellcheck plugin for CKEditor

## SCREENSHOTS
![Preview](/preview.png)

## AUTOHRS
- [Richard Willis](https://github.com/badsyntax/jquery-spellchecker),
- [wojtekel](http://mojemiejsce-wojtekel.rhcloud.com).

## CONFIGURATION
jqueryspellchecker/plugin.js
- replace 'pl' with desired language code where 'lang'.

## INSTALLATION
1. Install aspell.
2. Install php-enchant or php-pspell and libpspell-dev.
3. In jqueryspellchecker/plugin.js:
- replace 'enchant' with 'pspell' where 'driver' if installed second one or skip this step otherwise.
4. Move jqueryspellchecker directory to CKEditors plugin directory.
5. Move css, js and webservices directories to CKEditors directory.
6. Append 'jqueryspellchecker' to 'extraPlugins'.
