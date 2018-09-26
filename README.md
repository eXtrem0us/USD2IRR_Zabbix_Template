# USD to IRR Zabbix Template
You just need to follow these 4 steps:<br/>
1. install <code>lynx</code> on the server with <code>zabbix-agent</code>, which can access to bonbast.com (i.e. out of Iran) <br/>
<code>sudo apt-get install lynx</code>
2. Import the <code>DollarPrice.xml</code> template file through Zabbix Panel <br/>
3. Copy the <code>userparameter_dollar.conf</code> file to <code>/etc/zabbix/zabbix_agentd.d</code> <br/>
4. Restart the zabbix agent: <code>sudo service zabbix-agent restart</code> <br/><br/>

Good Luck!
