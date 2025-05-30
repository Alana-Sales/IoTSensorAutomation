# RIR Network Trace & Latency Analysis

This project contains a collection of simulated network diagnostic tests (ping and traceroute) conducted against the websites of Regional Internet Registries (RIRs), along with ISP analysis using `whois` data.

## Contents

- `network_tests/`
  - `ping_results.txt`: Simulated latency results from pinging the main RIRs.
  - `tracert_*.txt`: Traceroute outputs showing the hops toward various RIR domains and Cisco.
  - `isp_analysis.txt`: Analysis of ISP responsibility and routing based on whois information.

## Targeted RIRs

- **RIPE** (Europe) – www.ripe.net  
- **AFRINIC** (Africa) – www.afrinic.net  
- **LACNIC** (Latin America) – www.lacnic.net  
- **ARIN** (North America) – www.arin.net  

## Purpose

Educational repository to demonstrate how basic network tools can be used to understand latency, routing paths, and ISP transitions across continents.

© 2025 – Alana 
