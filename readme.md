#steps to generate keyfile
*openssl rand -base64 768 > keyfile
*sudo chmod 400 keyfile
*sudo chown 999:999 keyfile
