# vagrant

# CONFIG

# Go to config/vagrant-local-example.yml and copy it to a file named config/vagrant-local.yml
# This file will be your configuration.

# At the top, enter your own personal GitHub token.

# Make sure the machine_name is "mais"

# Make sure your path_to_erec and path_to_cps are absolute urls, for instance mine is ~/code/erec-yii2.

# SETUP

# ~/EREC

Make sure your .env file in the erec-yii2 folder has the database named "erec".

# ~/CPS

Make sure your common/config/main-local.php uses a database named
 "cps"

# ~/VAGRANT

Just run "vagrant up". When it finishes, you should have domains available at `erec.dev`, `cps.dev`, and `phpMyAdmin`.
