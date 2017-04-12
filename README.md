# Django Common Passwords Validation

Django comes pre-packaged with the ability to validate user passwords against the top 1,000 most commonly used passwords. This file directly overwrites Django's and contains the top 10,000 most common passwords, vastly improving account security and resistance to password dictionary attacks.

This file should replace Django's existing file, found in (if you use virtual environments): \venv\Lib\site-packages\django\contrib\auth\common-passwords.txt.gz

Common-password-validation is still almost instant in my development environment and on my test server, despite now having 10 times as many comparisons to make.


Warning for the easily offended:  This file contains some offensive language, it turns out people can be pretty foul when choosing passwords that they think no-one will ever see! -_-
