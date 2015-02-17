## Sensu-Plugins-qmail

[![Build Status](https://travis-ci.org/sensu-plugins/sensu-plugins-qmail.svg?branch=master)](https://travis-ci.org/sensu-plugins/sensu-plugins-qmail)
[![Gem Version](https://badge.fury.io/rb/sensu-plugins-qmail.svg)](http://badge.fury.io/rb/sensu-plugins-qmail)
[![Code Climate](https://codeclimate.com/github/sensu-plugins/sensu-plugins-qmail/badges/gpa.svg)](https://codeclimate.com/github/sensu-plugins/sensu-plugins-qmail)
[![Test Coverage](https://codeclimate.com/github/sensu-plugins/sensu-plugins-qmail/badges/coverage.svg)](https://codeclimate.com/github/sensu-plugins/sensu-plugins-qmail)
[![Dependency Status](https://gemnasium.com/sensu-plugins/sensu-plugins-qmail.svg)](https://gemnasium.com/sensu-plugins/sensu-plugins-qmail)

## Functionality

## Files
 * bin/check-qmailq

## Usage

## Installation

Add the public key (if you haven’t already) as a trusted certificate

```
gem cert --add <(curl -Ls https://raw.githubusercontent.com/sensu-plugins/sensu-plugins.github.io/master/certs/sensu-plugins.pem)
gem install sensu-plugins-qmail -P MediumSecurity
```

You can also download the key from /certs/ within each repository.

#### Rubygems

`gem install sensu-plugins-qmail`

#### Bundler

Add *sensu-plugins-disk-checks* to your Gemfile and run `bundle install` or `bundle update`

#### Chef

Using the Sensu **sensu_gem** LWRP
```
sensu_gem 'sensu-plugins-qmail' do
  options('--prerelease')
  version '0.0.1'
end
```

Using the Chef **gem_package** resource
```
gem_package 'sensu-plugins-qmail' do
  options('--prerelease')
  version '0.0.1'
end
```

## Notes
