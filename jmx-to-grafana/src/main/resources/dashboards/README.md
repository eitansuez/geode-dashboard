# Geode - Grafana Dashboards
Following sample Grafana dashboards visualize various Geode JMX metrics. Use them as templates to build your own dashboards. 

| Dashboard File | Description |
| ------------- | ------------ |
| [GeodeClusterView.json](./GeodeClusterView.json) ![Apache Geode Cluster View Dashboards](../../../../../doc/GeodeClusterViewSmall.png)| The cluster view is a high-level overview of the Geode distributed system. Cluster view show statistics such as memory usage, JVM pauses, and throughput. You can use the cluster view to drill down into details for individual members and regions in the distributed system. | 
| [GeodeMembersView.json](./GeodeMembersView.json) ![Apache Geode Members View Dashboards](../../../../../doc/GeodeMembersViewSmall.png)| Displays information for individual Geode members in the Cluster. Such as the number of regions, memory, threads ports. | 
| [GeodeMembersCombinedView.json](./GeodeMembersCombinedView.json) ![Apache Geode Members Combined View Dashboards](../../../../../doc/GeodeMembersCombinedViewSmall.png) | Can combine, correlate and compare metrics from multiple Members  | 
| [GeodeRegionView.json](./GeodeRegionView.json) | The Region View provides a comprehensive overview for individual Regions in the Geode distributed system | 

## Import Dashboards
* By default `jxm-to-grafana` loads all metrics series in the `GeodeJmx` InfluxDB database. Make sure that `GeodeJmx` is defined as Grafana datasource. 
* From Grafana's `Dashboards` menu select `Import` option and upload one of the predefined json dashboards.  
![Apache Geode Import Grafana Dashboards](../../../../../doc/ImportDashboard.png)
 