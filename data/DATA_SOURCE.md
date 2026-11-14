# Data Source

## Alibaba Cluster Trace

**Dataset Name:** Alibaba Cluster Trace: Microservices v2022  
**Source:** https://github.com/alibaba/clusterdata/tree/master/cluster-trace-microservices-v2022  
**Date Accessed:** November 13, 2026  
**Description:** Contains 13 days of microservice measurements from Alibaba's production infrastructure, including normalized CPU and memory utilization, call rates, and response times.  
**License:** Publicly available for research; no explicit license specified in the repository.  
**Relevant Variables:** `timestamp`, `msname`, `msinstanceid`, `nodeid`, `cpu_utilization`, `memory_utilization`, `providerrpc_rt`, `providerrpc_mcr`, `http_rt`, `http_mcr`.

## RIPE Atlas

**Dataset Name:** RIPE Atlas Public Network Measurements  
**Source:** https://atlas.ripe.net/  
**API:** https://atlas.ripe.net/api/v2/  
**Date Accessed:** November 13, 2026  
**Description:** Contains network measurements collected from geographically distributed probes and anchors. The ping measurements are used to calculate network latency between different geographic locations.  
**License:** Publicly available for research under the RIPE Atlas Service Terms and Conditions.  
**Relevant Variables:** `timestamp`, `prb_id`, `msm_id`, `avg`, `min`, `max`, geographic location, and destination address.

## Cloudflare Containers

**Dataset Name:** Cloudflare Containers Pricing  
**Source:** https://developers.cloudflare.com/containers/platform/pricing/  
**Date Accessed:** November 13, 2026  
**Description:** Published pricing for computing resources, including CPU, memory, and disk usage. These figures are used as a baseline for estimating infrastructure costs and do not represent Cloudflare's actual operating expenses.  
**License:** Publicly available pricing documentation.  
**Relevant Variables:** vCPU capacity, memory capacity, disk capacity, cost per vCPU-second, cost per GiB-second, and cost per GB-second.