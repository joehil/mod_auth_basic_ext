# mod_auth_basic_ext
Extended Basic Authentication for Apache Webserver

This is an extended version of the Basic Authentication Module for Apache Webserver. It does the same thing as the original module and has one extra feature:

If you send a request containing the header "X-Suppress-Auth-Popup: On" the Popup that the browser shows with basic authentications will be suppressed.

Please do NOT use mod_auth_basic_ext together with mod_auth_basic.
