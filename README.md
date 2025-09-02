# Prestashop module for Picsoo

### This Prestashop module allows to transfert data between Picsoo and Prestashop.

Please, read the documentation first. 
Any problems/bugs/suggestions should be reported here in Github.

## Current/Last version : 1.7.0

### IMPORTANT :

- this module has been tested on Prestashop 8.1.2 with PHP 7.4.33
- before installing a new version, you need to :
    - MAKE A BACKUP OF YOUR DATA !
    - un-install the previous version first; don't perform an update !

- after having downloaded the zip, you need to edit the file Picsoo_ws.php from the zip; it's located in the '[root]/modules/picsoo/libs' folder (+/- line #25) and change :

    private $UserName  = 'mycompany@picsoo.eu';<br>
    private $Password  = 'abcd12345';

    >> by replacing the email and password with those you log in Picsoo

- the process can be very long; sometimes even several hours !!! this is due to the complexity of Prestashop -- be patient !
  
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

 ### RESTRICTIONS :
    - only new items/products from Picsoo are transferred to Prestashop, no update available at this moment (future development)
    - Per restriction of Prestashop, only the pictures with format JPG and PNG are transferred from Picsoo.

### What's new in the latest version : 

- First release ```... ...```. 
- 1.2.0 March 19th, 2024:
  - ...
- 1.3.0 April 9th, 2024:
  - ...
- 1.4.0 
  - ...
- 1.5.0 May 6th, 2024:
  - modifications have been made in Picsoo; so, it's necessary to upgrade to this version.
  - several bugs fixed.
- 1.6.0 June 16th, 2025:
  - several bugs fixed.
  - added checkbox in parameters to send or not quantities from Prestashop to Picsoo (default = false)
- 1.7.0 September 2nd, 2025:
  - BUG FIXED : export product : when a product has no image, bug on getimagesize with "Path cannot be empty"
  - BUG FIXED : export customer : error on $result['IsSuccess'] with "Cannot access offset of type string on string"

## Credits & copyright

* (c) [Picsoo.eu](https://picsoo.eu/).

