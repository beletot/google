In order to use this module, you will have to generate a public/private
keypair[1], and install the xmlsec commandline tool[2].

Also, please note that this only works on Google Apps instances that
have API access (in other words, only Enterprise and Education domains).

[1] http://code.google.com/support/bin/answer.py?answer=71864&topic=12142
	Note that the private key must be in pem format, and the public key
	must be in der format. Make sure to note whether the keys are DSA
	or RSA format, and place them in a location accessible to the
	webserver.
[2] http://www.aleksey.com/xmlsec/
