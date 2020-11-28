Kibana Email Alert
==================

This role installs a service that watches journald for kibana log and if matches with defined pattern, then sends an email
alert to specified email address.

Role Variables
--------------
KIBANA_EMAIL_ALERT_TO_EMAIL - Which email address to use when sending alert

Dependencies
------------

Kibana, Journald
