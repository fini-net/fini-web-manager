# Manual steps

	cd ~/Documents/git/simp_le/
	./venv.sh 
	PATH=`pwd`/venv/bin:$PATH
	~/Documents/git/simp_le/simp_le.py --email chicks.net@gmail.com -f account_key.json -f fullchain.pem -f key.pem -f cert.pem -d dev.sepi.fini.net:/www/sepi-dev/docroot/
