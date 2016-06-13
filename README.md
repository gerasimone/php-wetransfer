# php-wetransfer

PHP script for downloading WeTransfer files (https://www.wetransfer.com/) from PHP, extendend support for shortned URLs

# Usage

You should have a we transfer address similar to either:  
https://www.wetransfer.com/downloads/XXXXXXXXXX/YYYYY or  
https://www.wetransfer.com/downloads/XXXXXXXXXX/YYYYY/ZZZZZ or
https://we.tl/soMEthINgElsE

Include the function code somewhere, and simply call the function:

    getWeTransferFile_shortUrl('https://we.tl/soMEthINgElsE','wetra.zip');

# Acknowledgements

Based on the python script:  https://github.com/superalex/py-wetransfer and forked from https://github.com/pseux/php-wetransfer
