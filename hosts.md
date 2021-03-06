Virtual Servers
===============

<table>
  <thead>
    <tr>
      <th>Host</th>
      <th>Domain</th>
      <th>OS</th>
      <th>IP</th>
      <th>Resources</th>
      <th>Comments</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>chat</td>
      <td>civicrm.org</td>
      <td>Ubuntu 16.04 LTS (Xenial)</td>
      <td>140.211.167.153</td>
      <th>cores=2 ram=2gb root=20gb (updated: 2016-04-23)</th>
      <td>Mattermost, Nginx</td>
    </tr>
    <tr>
      <td>java-prod</td>
      <td>civicrm.osuosl.org</td>
      <td>Ubuntu 16.04 LTS (Xenial)</td>
      <td>140.211.167.141</td>
      <th>cores=2 ram=6gb root=25gb (updated: 2016-05-24)</th>
      <td>Confluence, JIRA, MySQL, Apache</td>
    </tr>
    <tr>
      <td>java-test</td>
      <td>civicrm.osuosl.org</td>
      <td>Ubuntu 14.04 LTS (Trusty Tahir)</td>
      <td>140.211.167.143</td>
      <th>cores=2 ram=2 hdd=27gb (updated: 2013-11-27)</th>
      <td>OFFLINE - Confluence, JIRA, MySQL, Apache</td>
    </tr>
    <tr>
      <td>log</td>
      <td>civicrm.osuosl.org</td>
      <td>Ubuntu 16.04 LTS (Xenial)</td>
      <td>140.211.167.189</td>
      <th>cores=2 ram=2gb hdd=39gb (updated: 2015-09-25)</th>
      <td>Logstash</td>
    </tr>
    <tr>
      <td>manage</td>
      <td>civicrm.osuosl.org</td>
      <td>Ubuntu 12.04 LTS (Precise Pangolin)</td>
      <td>140.211.167.144</td>
      <th>cores=2 ram=2gb root=15gb (updated: 2014-10-27)</th>
      <td>Puppet Master, slapd, phpldapadmin -- all firewalled to prevent remote access. For LDAP management instructions, login via SSH and run "sudo cat /root/ldap-notes.txt"</td>
    </tr>
    <tr>
      <td>svn</td>
      <td>civicrm.osuosl.org</td>
      <td>Ubuntu 12.04 LTS (Precise Pangolin)</td>
      <td>140.211.167.145</td>
      <th>cores=2 ram=2gb hdd=10gb (updated: 2013-11-27)</th>
      <td>Apache, SVN (read only), ViewVC</td>
    </tr>
    <tr>
      <td>test-debian6-1</td>
      <td>civicrm.osuosl.org</td>
      <td>Debian Squeeze</td>
      <td>140.211.167.146</td>
      <th>cores=2 ram=4gb root=17gb (updated: 2014-10-27)</th>
      <td>Jenkins (Slave), Apache, MySQL, Drupal, Drush</td>
    </tr>
    <tr>
      <td>test-master</td>
      <td>civicrm.osuosl.org</td>
      <td>Ubuntu 12.04 LTS (Precise Pangolin)</td>
      <td>140.211.167.147</td>
      <th>cores=2 ram=3gb root=12gb (updated: 2014-10-27)</th>
      <td>Jenkins (Master), Apache (for HTTPS), Tomcat (for AJP)</td>
    </tr>
    <tr>
      <td>test-ubu1204-1</td>
      <td>civicrm.osuosl.org</td>
      <td>Ubuntu 12.04 LTS (Precise Pangolin)</td>
      <td>140.211.167.149</td>
      <th>cores=2 ram=4 root=20gb (updated: 2014-10-27)</th>
      <td>Jenkins (Slave), Apache, MySQL, Drupal/Drush, CiviCRM</td>
    </tr>
    <tr>
      <td>test-ubu1204-2</td>
      <td>civicrm.osuosl.org</td>
      <td>Ubuntu 12.04 LTS (Precise Pangolin)</td>
      <td>140.211.167.149</td>
      <th>cores=2 ram=4gb root=12gb (updated: 2014-10-27)</th>
      <td>Jenkins (Slave), Apache, MySQL, Drupal/Drush, CiviCRM</td>
    </tr>
    <tr>
      <td>test-ubu1210-1</td>
      <td>civicrm.osuosl.org</td>
      <td>Ubuntu 12.10</td>
      <td>140.211.167.150</td>
      <th>cores=2 ram=4gb root=12gb (updated: 2014-10-27)</th>
      <td>Jenkins (Slave), Apache, MySQL, Drupal/Drush, CiviCRM</td>
    </tr>
    <tr>
      <td>www-cxn-2</td>
      <td>civicrm.osuosl.org</td>
      <td>Ubuntu 12.04 LTS (Precise Pangolin)</td>
      <td>140.211.167.175</td>
      <th>cores=2 ram=1.5gb root=10gb (updated: 2015-09-20)</th>
      <td>Apache, MySQL</td>
    </tr>
    <tr>
      <td>www-demo</td>
      <td>civicrm.osuosl.org</td>
      <td>Ubuntu 14.04 LTS (Trusty Tahir)</td>
      <td>140.211.167.151</td>
      <th>cores=2 ram=4gb root=17gb (updated: 2014-10-27)</th>
      <td>Apache, MySQL, Drupal, Joomla, WordPress, CiviCRM</td>
    </tr>
    <tr>
      <td>www-prod</td>
      <td>civicrm.osuosl.org</td>
      <td>Ubuntu 16.04 LTS (Xenial)</td>
      <td>140.211.167.152</td>
      <th>cores=2 ram=6gb root=25gb (updated: 2014-10-27)</th>
      <td>Nginx, MySQL, Drupal/Drush, SMF/forum.civicrm.org, alert.civicrm.org, docs.civicrm.org</td>
    </tr>
    <tr>
      <td>www-test</td>
      <td>civicrm.osuosl.org</td>
      <td>Ubuntu 16.04 LTS (Xenial)</td>
      <td>140.211.167.160</td>
      <th>cores=2 ram=3gb root=15gb (updated: 2014-10-27)</th>
      <td>http auth: civicrm/civicrm<br />Nginx, MySQL, Drupal/Drush</td>
    </tr>
    <tr>
      <td>backup-1</td>
      <td>Google Cloud</td>
      <td>Ubuntu 16.04 LTS (Xenial)</td>
      <td>107.178.223.170</td>
      <th>cores=1 ram=1.7gb root=25gb (updated: 2015-10-10)</th>
      <td>Backups</td>
    </tr>
    <tr>
      <td>test-ubu1204-5</td>
      <td>OVH</td>
      <td>Ubuntu 12.04 LTS (Precise Pangolin)</td>
      <td>192.95.2.130</td>
      <th>cores=4 ram=20gb root=50gb (updated: 2016-04-22)</th>
      <td>Tests</td>
    </tr>
    <tr>
      <td>test-ubu1604-1</td>
      <td>OVH</td>
      <td>Ubuntu 16.04 LTS (Xenial Xerus)</td>
      <td>192.95.2.131</td>
      <th>cores=4 ram=8gb root=50gb (updated: 2015-04-22)</th>
      <td>Tests</td>
    </tr>
    <tr>
      <td>botdylan</td>
      <td>OVH</td>
      <td>Ubuntu 16.04 LTS (Xenial Xerus)</td>
      <td>192.95.2.132</td>
      <th>cores=2 ram=2gb root=25gb (updated: 2015-04-22)</th>
      <td>Tests</td>
    </tr>
  </tbody>
</table>

Physical Servers
================

<table>
  <thead>
    <tr>
      <th>Host</th>
      <th>Domain</th>
      <th>OS</th>
      <th>IP</th>
      <th>Resources</th>
      <th>Comments</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>biryani</td>
      <td>osuosl.org</td>
      <td>Ubuntu 12.04 LTS (Precise Pangolin)</td>
      <td>140.211.166.57</td>
      <td>cores=2 ram=4gb lvmvg=175gb (updated: 2014-11-09)</td>
      <td>Releaser. L10n processor. download.civicrm.org, latest.civicrm.org.</td>
    </tr>
    <tr>
      <td>civicrm-sushi-spare</td>
      <td>osuosl.org</td>
      <td>Ubuntu 16.04 LTS (Xenial)</td>
      <td>140.211.166.28</td>
      <td>cores=2(Pentium 1403v2) ram=32gb hdd=3x600gb(10k,2.5)</td>
      <td>1+3yr wty (2015-2019?)</td>
    </tr>
    <tr>
      <td>padthai</td>
      <td>civicrm.org</td>
      <td>Debian 8</td>
      <td>167.114.158.208</td>
      <td>cores=4/8 (E5-1620v2) ram=64gb ssd=3x300gb (updated: 2016-04-07)</td>
      <td>virt-install</td>
    </tr>
    <tr>
      <td>civicrm1</td>
      <td></td>
      <td>?? (Ganeti)</td>
      <td></td>
      <td>
<pre>
CPU: 2 x Intel Xeon E5-2407, 2.2GHz (4-Core, 10MB Cache, 80W) 32nm
RAM: 48GB (6 x 8GB DDR3-1600 ECC Registered 2R DIMMs) Operating at 1600 MT/s Max
NIC: Dual Intel 82574L Gigabit Ethernet Controllers - Integrated
Management: Integrated IPMI 2.0 & KVM over LAN
Hot-Swap Drive - 1: 500GB Western Digital VelociRaptor (6Gb/s, 10K RPM, 64MB Cache) 3.5" SATA 
Hot-Swap Drive - 2: 500GB Western Digital VelociRaptor (6Gb/s, 10K RPM, 64MB Cache) 3.5" SATA 
Hot-Swap Drive - 3: 500GB Western Digital VelociRaptor (6Gb/s, 10K RPM, 64MB Cache) 3.5" SATA 
Hot-Swap Drive - 4: 180GB Intel 520 Series MLC (6Gb/s) 2.5" SATA SSD
Optical Drive: No Drive
Power Supply: Redundant 400W Power Supply with PMBus and I2C
Selected
Warranty: Std 3-Yr Warranty + 3-Yr Expanded Warranty, Next Business Day On Site - Spare Parts Req
</pre>
      </td>
    </tr>
    <tr>
      <td>civicrm2</td>
      <td></td>
      <td>?? (Ganeti)</td>
      <td></td>
      <td>
<pre>
CPU: 2 x Intel Xeon E5-2407, 2.2GHz (4-Core, 10MB Cache, 80W) 32nm
RAM: 48GB (6 x 8GB DDR3-1600 ECC Registered 2R DIMMs) Operating at 1600 MT/s Max
NIC: Dual Intel 82574L Gigabit Ethernet Controllers - Integrated
Management: Integrated IPMI 2.0 & KVM over LAN
Hot-Swap Drive - 1: 500GB Western Digital VelociRaptor (6Gb/s, 10K RPM, 64MB Cache) 3.5" SATA 
Hot-Swap Drive - 2: 500GB Western Digital VelociRaptor (6Gb/s, 10K RPM, 64MB Cache) 3.5" SATA 
Hot-Swap Drive - 3: 500GB Western Digital VelociRaptor (6Gb/s, 10K RPM, 64MB Cache) 3.5" SATA 
Hot-Swap Drive - 4: 180GB Intel 520 Series MLC (6Gb/s) 2.5" SATA SSD
Optical Drive: No Drive
Power Supply: Redundant 400W Power Supply with PMBus and I2C
Warranty: Std 3-Yr Warranty + 3-Yr Expanded Warranty, Next Business Day On Site - Spare Parts Req
</pre>
      </td>
    </tr>
  </tbody>
</table>
