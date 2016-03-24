# Django-Common-Passwords
My "top 10k most common passwords validation" replacement text file.

Django comes prepackaged with an option to validate user passwords against the top 1,000 most common passwords. This file directly overwrites Django's and contains the top 10,000 most common passwords, vastly improving account security.

This file should overwrite Django's existing file, found in (if you use virtual environments): \venv\Lib\site-packages\django\contrib\auth\common-passwords.txt.gz

Common-password-validation is still almost instant on my test server, despite now having approx. 10 times as many comparisons to make.
