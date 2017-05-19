include /usr/local/share/luggage/luggage.make
TITLE=CloudFrontMiddleware_Test
REVERSE_DOMAIN=com.github.aaronburchfield.cloudfrontmiddleware
PACKAGE_VERSION=1.0
KEY_FILE=July_17_key
PAYLOAD=pack-middleware-key\
	      pack-script-postinstall

pack-middleware-key:
		@sudo mkdir -p ${WORK_D}/usr/local/munki
		@sudo ${CP} ./${KEY_FILE}.pem ${WORK_D}/usr/local/munki
		@sudo chown root:wheel ${WORK_D}/usr/local/munki/${KEY_FILE}.pem
		@sudo chmod 400 ${WORK_D}/usr/local/munki/${KEY_FILE}.pem
