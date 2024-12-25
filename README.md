# Scanner PHPUNIT RCE | VulnerabilityScanner for PHPUnit RCE

A specialized vulnerability scanner developed to identify and interactively exploit the Remote Code Execution (RCE) vulnerability in PHPUnit's eval-stdin.php. This vulnerability affects PHPUnit versions before 4.8.28 and 5.x before 5.6.3 and allows remote attackers to execute arbitrary PHP code via HTTP POST data.

Contact Me : https://t.me/odayturkeyzsec

# Description of the Vulnerability:
The Util/PHP/eval-stdin.php file in PHPUnit, in versions prior to 4.8.28 and 5.x before 5.6.3, has a vulnerability allowing remote attackers to execute arbitrary PHP code. An attacker can exploit this by sending HTTP POST data starting with a <?php substring. This poses a significant threat to sites with an exposed /vendor directory, giving external access to the /vendor/phpunit/phpunit/src/Util/PHP/eval-stdin.php URI.

![image](https://github.com/user-attachments/assets/39b2414e-233e-424c-aa8b-bf8caba2b633)


## Requirements
- Python 3.10.2 
## Supported Os
- Linuxer
- Windows
## Get start with
```
$ pip install requests
$ pip install colorama
$ git clone https://github.com/odayturkeyzsec/Scanner-PHPUNIT-RCE/
$ cd Scanner-PHPUNIT-RCE
$ python 0dayphpunit.py
```
## Footprints Notes
- By using this tool, you agree that you are using it for educational purposes only and that you will not use it for any illegal activity. You also agree to bear all risks associated with the use of this tool. I will not be responsible for direct or indirect damage caused by the use of this tool. Don't
```
```
## Author
- Odayturkeyzsec
```
```
## Contacts
Telegram : [t.me/odayturkeyzsec](https://t.me/odayturkeyzsec)
