# Redmine OpenID Connect Plugin #

**Note** *This plugin is at the moment, a proof of concept (POC). Further coding needs to be added to ensure security.*

## Introduction ##
This is a plugin based on the implementation of redmine_cas. It redirects to a SSO server bypassing the original Redmine login authentication and using the SSO server authentication in it's place.

## Usage ##
1. Go to your Redmine plugins directory.
2. Clone/copy this plugin.
3. Restart your server
4. Login as administrator and head over to the plugins page.
5. Open the configuration page for redmine openid connect plugin.
6. Fill in the details.
7. Go to your SSO server and add this url as a registered login url and logout url respectively:

```
http(or s)://your-host-url/has_authorization
```
```
http(or s)://your-host-url
```

Enjoy!