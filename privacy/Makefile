all: sign

sign:
	gpg2 --clearsign index.html
	mv -f index.html.asc signature.txt
