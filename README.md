# ngx_http_blacklist

ngx_http_blacklist
ngx_http_blacklist provide the blacklisting capabilitiy for NGINX.

The module is extremely useful in the current internet world where Cyber Security attack is prevalent.
It enables you to blacklist IP addresses that try to attack your infrastructure or those that have been flagged as malicious by threat intelligence platforms (like abuseipdb.com) due to their persistent behavior of committing malicious acts.

Setup
This module uses the memcached server as data storage to store store the blacklsted IP addresses. With memcached server, the module will be able to get the consistent response time when validating an IP address.

<TODO>

Configuration
<TODO>
  
