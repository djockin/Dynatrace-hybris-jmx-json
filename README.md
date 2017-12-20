# Dynatrace-hybris-jmx-json
A JSON repostory for custom JMX metrics for Hybris running on Dynatrace

## Requirements
* Dynatrace Environment with OneAgent Installed on Hybris hosts
* Dynatrace Environment permissions to upload custom plugins

## Installation on your Dynatrace Tenant
* From the 'Settings' -> 'Monitoring' -> 'Monitored Technologies' section, select 'Custom plugins' tab
* Click on the button 'Upload Plugin' and select the hybris.json files you wish to use.

## Limitations
* JMX monitoring is highly dynamic. If a particular metric doesn’t exist in your JVM, it's not an error—the metric simply isn't available.

## Important links:

https://www.dynatrace.com/support/help/monitoring-plugins/application-plugins/how-do-i-monitor-jmx-metrics-in-my-java-applications/ 

 https://dynatrace.github.io/plugin-sdk/api/plugin_json_apidoc.html
