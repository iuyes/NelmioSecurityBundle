### 1.6.0 (2015-02-01)

  * Added a `forced_ssl.hsts_preload` flag to allow adding the preload attribute on HSTS headers

### 1.5.0 (2015-01-01)

  * Added ability to have different configs for both reported and enforced CSP rules
  * Added support for ALLOW and ALLOW FROM syntaxes in the Clickjacking Protection
  * Added support for HHVM and PHP 5.6
  * Fixed enabling of cookie signing when the cookie list is empty

### 1.4.0 (2014-02-13)

  * Added default controller to log CSP violations
  * Added a flag to remove outdated non-standard CSP headers and only send the `Content-Security-Policy` one

### 1.3.0 (2014-01-08)

  * Added support for setting the X-Content-Type-Options header

### 1.2.0 (2013-07-29)

  * Added Content-Security-Policy (CSP) 1.0 support
  * Added forced_ssl.whitelist property to define URLs that do not need to be force-redirected
  * Fixed session loss bug on 404 URLs in the CookieSessionHandler

### 1.1.0 (2013-03-27)

  * Added a cookie session storage (use only if really needed, and combine it with `encrypted_cookie`)
  * Fixed error reporting if mcrypt is not enabled and you try to use encryption

### 1.0.0 (2013-01-08)

  * Initial release
