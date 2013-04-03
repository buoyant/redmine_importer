Redmine Issue Importer plugin for Rails 3.x
================

Redmine Importer allows importing issues in bulk from .csv files. Fields will default to name-based mapping but can be overridden at the confirmation screen. Existing issues can be updated, and issue relationships and custom fields are supported.

similar to importer plugin(http://www.redmine.org/plugins/importer). 

Download the plugin to your application/root/folder/plugins directory. Be sure to maintain the correct folder name, ‘redmine_importer’.

Run ‘rake redmine:plugins:migrate RAILS_ENV=production’

Restart your redmine as appropriate (e.g., ‘rails s -e production’)

Go to the Admin/Projects/../Modules

Enable “Importer”

credits Leo Hourvitz
