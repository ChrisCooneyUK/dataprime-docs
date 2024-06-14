DataPrime is a syntax targeted specifically at the analysis of complex telemetry data. The existing tools were great 10 years ago, but they're no longer fit for purpose. DataPrime aims to solve that problem.

```
source logs | filter ipInSubnet($d.client_ip, '10.0.0.0/8')
```
