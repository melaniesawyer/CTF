# Broken RSA

**Category:** Cryptography
**Description:**

> This RSA service seems to be broken. They encrypt the flag and send it to you each time... but they throw out the private key and you never get to see it. Any ideas on how to recover the flag?

## Hint
> Connect from the shell with 'nc vuln.picoctf.com 6666'. Read up on RSA and look at broken_rsa_source.py (the implementation of the shell) to figure out why it might be an unsecurely designed script!
