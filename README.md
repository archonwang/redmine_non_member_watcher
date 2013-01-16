# Non member watcher

Redmine plugin that adds new system role "Non member watcher".

This plugin allows to set permissions for watchers that are not members of a
project. For this purpose there is a new builtin role "Non member watcher" and
new issues visibility option "Issues watched by the user".
Non member watchers can receive email notifications if you switching on new
permission "Receive email notifications" (Note: permission "View issues" must be enabled).

## Installation

Follow the plugin installation procedure at http://www.redmine.org/wiki/redmine/Plugins.

## Testing

RAILS_ENV=test rake redmine:plugins:test NAME=redmine_non_member_watcher

## Compatibility

This version supports only redmine 2.x. See [redmine-1.x](https://github.com/Undev/redmine_non_member_watcher/tree/redmine-1.x) branch for Redmine 1.x.

