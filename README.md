# haproxy-categorized

Use this script to categorized your haproxy configuration.
You can spread your .cfg file to some folder instead of using only single haproxy.cfg

## STEP
1. first, install colordiff via yum/apt.
2. create conf.d folder on /etc/haproxy
3. create config file on conf.d
   example : 00-defaults.cfg, 01-global.cfg, 02-web.cfg
4. execute haconfig.sh to concate the conf file and reload the service
