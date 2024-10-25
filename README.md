# Threat Detection Using ELK

## Overview

This project focuses on utilizing the ELK Stack (Elasticsearch, Logstash, and Kibana) for effective threat detection in a cybersecurity context. By leveraging the power of ELK, we can monitor, analyze, and visualize potential threats in real time. The project explores various techniques for identifying malicious activities, specifically through the analysis of registry keys, PowerShell scripts, and more.

### Key Features

- **Registry Monitoring**: Detects persistence mechanisms by analyzing changes in registry keys, particularly in locations that attackers frequently target.
- **PowerShell Analysis**: Investigates PowerShell scripts executed on the system to identify any potentially malicious activities or scripts run remotely.
- **Visualization**: Utilizes Kibana to create visual representations of the data, making it easier to identify patterns and anomalies in the logs.

### Blog Link

For more details on the methodologies and findings of this project, check out my blog: [Threat Detection Using ELK](https://medium.com/@omhg22/threat-detection-with-elastic-5c179fa4c7fe).

## ELK Installation

1. **Elasticsearch**: Follow the official [Elasticsearch installation guide](https://www.elastic.co/guide/en/elasticsearch/reference/current/install-elasticsearch.html).
2. **Logstash**: Follow the official [Logstash installation guide](https://www.elastic.co/guide/en/logstash/current/installing-logstash.html).
3. **Kibana**: Follow the official [Kibana installation guide](https://www.elastic.co/guide/en/kibana/current/install.html).
