## [3.1.3]

### FIXES:

  * Fix puppet-lint linenumber config change in Rakefile.

### IMPROVEMENTS:

  * Upgraded all Puppet gems; tested with Ruby 2.3.3.

## [3.1.2]

### IMPROVEMENTS:

  * Upgraded all Puppet gems; tested with Ruby 2.3.3.

## [3.1.1]

### IMPROVEMENTS:

  * Upgraded all Puppet gems; tested with Ruby 2.3.3.

## [3.1.0]

### IMPROVEMENTS:

  * Upgraded all Puppet gems; tested with Ruby 2.3.1.
  * Vagrant init.sh script installs latest `puppet-agent` on test VM.
  * Silenced Vagrant init.sh script output.

## [3.0.12]

### IMPROVEMENTS:

  * Add back an `integ` Rake task to automatically run Vagrant. This task runs `spec_prep` Rake task prior to running Vagrant.

## [3.0.11]

### IMPROVEMENTS:

  * Upgrade to `puppet-lint` 2.0.0.

## [3.0.10]

### FIXES:

  * Use `https://apt.puppetlabs.com/pubkey.gpg` for puppetlabs GPG key; fixes puppetlabs' ubuntu vagrant box.

## [3.0.9]

### IMPROVEMENTS:

  * Switch to `https` for rubygems.org in the Gemfile template.

## [3.0.8]

### IMPROVEMENTS:

  * Updated `puppet` gem in Gemfile to 4.5.1.

## [3.0.6]

## [3.0.5]

## [3.0.4]

### IMPROVEMENTS:

  * Adding `vagrant-cachier` support in Vagrantfile.

## [3.0.3]

## [3.0.2]

## [3.0.1]

## [3.0.0]

### FEATURES:

  * Upgraded to support Puppet 4+.
