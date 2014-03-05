source 'https://rubygems.org'
 
gem 'rails',          '~>2.3.18'
gem 'rake'

# gems pegged because of ruby 1.8
gem 'mime-types',     '1.23'
gem 'rubyzip',        '0.9.9',  :require => 'zip/zip'
gem 'sanitize',       '2.0.3'

gem 'json',           '>= 1.7.7'
gem 'nokogiri',       '1.5.5' # only pegged because nokogiri 1.5.9 installation fucking up on OSX
gem 'curb'
gem 'calais',         '>= 0.0.11'
gem 'rest-client',    '>= 1.0.3',  :require => 'rest_client'
gem 'bcrypt-ruby',    '>= 2.1.2',  :require => 'bcrypt'
gem 'right_aws',      '>= 2.0.1'        # Our patched version.
gem 'aws-sdk',        '>= 1.7.1'
gem 'pg',             '>= 0.11.0'
gem 'jammit',         '>= 0.5.0'
gem 'closure-compiler'
gem 'docsplit',       '>= 0.6.4'
gem 'sunspot_rails',  '>= 1.3.3'
# running a pre-release to fix rake sunspot:solr:stop task bug
# https://github.com/sunspot/sunspot/pull/221
gem 'sunspot_solr',   '>= 2.0.0.pre.120925'
gem 'rdiscount',      '>= 1.6.5'
gem 'fastercsv',      '>= 1.5.3'

gem 'omniauth',                '>= 1.0'
gem 'omniauth-twitter',        '>= 0.0.13'
gem 'omniauth-facebook',       '>= 1.4.0'
gem 'omniauth-google-oauth2',  '>= 0.1.13'

gem 'cloud-crowd'
gem 'pdftailor'
gem 'sqlite3'

group :translations do
  # for downloading the translations from google spreadsheet
  gem 'google_drive'
  # securely ask for username/password for access to translation spreadsheet
  gem 'highline'
end
