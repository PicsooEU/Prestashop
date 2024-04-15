# Prestashop module for Picsoo

### This Prestashop module allows to transfert data to/from Picsoo from/to Prestashop.

Please, read the documentation first. 
Any problems/bugs/suggestions should be reported here in Github.

## Current version : 1.3.0

### IMPORTANT :

- before installing a new version, you need to un-install the previous version first; don't perform an update !

- after having downloaded the zip, you need to edit the file Picsoo_ws.php from the zip; it's located in the 'libs' folder (+/- line 25) and change :

    private $UserName  = 'mycompany@picsoo.eu';<br>
    private $Password  = 'abcd12345';

by replacing the email and password with those you log in Picsoo

- if you have trouble while transferring huge amount of data and you get a 500 error message from the server; please, read this :

  https://prestashop.com/blog/tech-en/what-is-the-http-500-error-and-how-can-i-fix-it-in-my-prestashop-online-store/

  3. Waiting time has expired
        Each server has its own waiting time, which determines how long a script will run.

        If the function or script exceeds this time limit, you will receive a 500 error.

        Here are the PrestaShop scripts that may take too long to load:

            Importing CSV files.
            Backup files.
            Loading translations.
            Import/export.
            Regenerating miniature views.
            In most cases, the server time limit is 30 seconds, which is not enough for these scripts.

    >>> In this case, you should contact your host and ask them to change this setting (at least temporarily).

### What's new in the latest version : 

- First release ```... ...```. 
- 1.2.0 March 19th, 2024:
  - ...
- 1.3.0 April 9th, 2024:
  - ...


## Credits & copyright

* (c) [Picsoo.eu](https://picsoo.eu/).

