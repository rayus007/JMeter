# JMeter

POC to use JMETER with https://blazedemo.com/

- Created a Thread Group (Click right > Add > Thread Group)
- Add HTTP Test Script Recorder (non-Test Elements)
- Add View Results Tree (Listener)
- Add aggregate Report



- Browser Extension used to mimic Proxy: Foxy Proxy





Issue got during recording steps: GET http://detectportal.firefox.com/success.txt

Mitigation: about:config
Set to false the rule: network.captive-portal-service.enabled




- Assertions:


- Variables and Data Set Config



In the step, click Add > Config Element > CSV Data Set Config.

Also prepare your csv file.


