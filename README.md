# SpluckCluster_Container
Plan to build up Cluster Splunk on Docker container
Initially, this plan includes 1 Indexers and 1 Search Head, Which menas 5 instances running (1 master node, 3 peer nodes and 1 SH). This plan.
Official Splunk image from:https://hub.docker.com/r/splunk/splunk/
This plan mainly focus on the port
Will add one/more extra clients to send syslog to HF (via syslog-ng)
Port retention for Splunk: https://docs.splunk.com/Documentation/Splunk/7.2.5/InheritedDeployment/Ports
