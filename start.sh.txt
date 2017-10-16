#!/bin/bash
service postfix start
service rspamd start
service rmilter start
service clamav-freshclam start
sleep 60
service clamav-daemon start
