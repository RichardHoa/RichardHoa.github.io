---
layout: page
title: Go network-latency-visualizer
importance: 1
category: fun
---

## Source code

You can view the source code here [here](https://github.com/RichardHoa/Network-Latency-Visualizer)

## Features

1. **Data Visualization**: Visualize network latency data over time in easy-to-understand charts.
2. **Network Latency Monitoring**: Perform regular network latency checks using the `ping` command. You can set the frequency of checks (from every 1 minutes to once a day) via a cron job to automate the process.
3. **Process Bandwidth Usage**: Track bandwidth usage by individual processes, displaying both incoming and outgoing data.
4. **Download & Upload Speed**: Measure and display your current download and upload speeds.

## Showcase

- **Process network usage chart**: These charts display the cumulative amount of data sent and received by processes since their creation. Note that the data shown is the total accumulated over time, not the current data transfer in any specific period.

  1. Received Network Data. This chart highlights the **top 3 processes** that have received the largest amount of data.
     {% include figure.liquid loading="eager" path="assets/img/received-network-data-chart.png" title="Received network data chart" class="img-fluid rounded z-depth-1" %}
  2. Sent Network Data. This chart highlights the **top 3 processes** that have sent the largest amount of data.
     {% include figure.liquid loading="eager" path="assets/img/sent-network-data-chart.png" title="Sent network data chart" class="img-fluid rounded z-depth-1" %}
  3. In addition to the charts, a detailed table with all processes and their network usage is displayed in the terminal. The processes are **ordered by the average amount of data received**.
     {% include figure.liquid loading="eager" path="assets/img/terminal-table.png" title="terminal table image" class="img-fluid rounded z-depth-1" %}

- **Network Latency Chart**: No need to explain more!
  1. Network latency chart
     {% include figure.liquid loading="eager" path="assets/img/network-latency-chart.png" title="network latency chart" class="img-fluid rounded z-depth-1" %}
  2. Speedtest chart
     {% include figure.liquid loading="eager" path="assets/img/speedtest-chart.png" title="speedtest chart" class="img-fluid rounded z-depth-1" %}
