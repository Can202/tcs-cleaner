# Tcs Cleaner

# Install:
do you need just curl
~~~
curl https://raw.githubusercontent.com/Can202/tcs-cleaner/main/installer | sudo bash
~~~
~~~
su root -c 'curl https://raw.githubusercontent.com/Can202/tcs-cleaner/main/installer | bash'
~~~
~~~
curl https://raw.githubusercontent.com/Can202/tcs-cleaner/main/installer | pkexec bash
~~~

## Execute:
### Please install curl and dialog
### curl and sudo
~~~
cd /tmp && sudo rm -vrf tcs-cleaner && sudo curl -LO https://raw.githubusercontent.com/Can202/tcs-cleaner/main/tcs-cleaner && sudo chmod a+x /tmp/tcs-cleaner && sudo /tmp/tcs-cleaner
~~~
### curl and su
~~~
su root -c 'cd /tmp && rm -vrf tcs-cleaner && curl -LO https://raw.githubusercontent.com/Can202/tcs-cleaner/main/tcs-cleaner && chmod a+x /tmp/tcs-cleaner && /tmp/tcs-cleaner'
~~~
### curl and pkexec
~~~
cd /tmp && rm -vrf tcs-cleaner && curl -LO https://raw.githubusercontent.com/Can202/tcs-cleaner/main/tcs-cleaner && chmod a+x /tmp/tcs-cleaner && pkexec /tmp/tcs-cleaner
~~~
