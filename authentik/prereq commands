# You can also use openssl instead: `openssl rand -base64 36`
sudo apt-get install -y pwgen
echo "PG_PASS=$(pwgen -s 40 1)" >> .env
echo "AUTHENTIK_SECRET_KEY=$(pwgen -s 50 1)" >> .env
# Skip if you don't want to enable error reporting
echo "AUTHENTIK_ERROR_REPORTING__ENABLED=true" >> .env