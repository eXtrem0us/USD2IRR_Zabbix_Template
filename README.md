# USD to IRR Zabbix Template
You just need to follow these 3 steps:<br/>
1. Import the <code>DollarPrice.xml</code> template file through Zabbix Panel <br/>
2. Copy the <code>userparameter_dollar.conf</code> file to <code>/etc/zabbix/zabbix_agentd.d</code> (on the server, which can access to bonbast.com, i.e. out of Iran) <br/>
3. Restart the zabbix agent: <code>sudo service zabbix-agent restart</code> <br/><br/>

Good Luck!
