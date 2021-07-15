
{
     "name": "bitcoinvietnam/bitcoinvn-php",
     "description": "A wrapper for consuming the API endpoints of bitcoinvn.io",
     "type": "library",
     "license": "MIT",
     "authors": [
         {
             "name": "Thong Ngo",
             "email": "quangthong1011@gmail.com"
         }
     ],
     "require": {
         "guzzlehttp/guzzle": "^6.3",
         "jms/serializer": "^1.13|^2.2.0",
         "doctrine/common": "^2.10"
     },
     "autoload": {
         "psr-4": {
             "BitcoinVietnam\\BitcoinVn.io\\": "src/"
         }
     },
     "require-dev": {
         "symfony/var-dumper": "^4.2"
     }
 }
