# burphmac
snippet copied from https://github.com/pentestpartners/snippets/blob/master/hmac.py
Code modified from PTP blog post "https://www.pentestpartners.com/security-blog/burp-hmac-header-extensions-a-how-to/" 
to work on custom HMAC implementation.

Python module must first be imported into Burp using extender function
Session options must then be modified to add session handling rules to add custom header.
