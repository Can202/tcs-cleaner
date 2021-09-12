# Tcs Cleaner

## Execute:
### Please install curl and dialog
### curl and sudo
~~~
cd /tmp && rm -vrf tcs-cleaner && curl -LO https://raw.githubusercontent.com/Can202/tcs-cleaner/main/tcs-cleaner && chmod a+x /tmp/tcs-cleaner && sudo /tmp/tcs-cleaner
~~~
### curl and su
~~~
cd /tmp && rm -vrf tcs-cleaner && curl -LO https://raw.githubusercontent.com/Can202/tcs-cleaner/main/tcs-cleaner && chmod a+x /tmp/tcs-cleaner && su -c '/tmp/tcs-cleaner'
~~~
### curl and pkexec
~~~
cd /tmp && rm -vrf tcs-cleaner && curl -LO https://raw.githubusercontent.com/Can202/tcs-cleaner/main/tcs-cleaner && chmod a+x /tmp/tcs-cleaner && pkexec /tmp/tcs-cleaner
~~~
