## Using pings
### ping three popular websites (for 5 or so packets each)
**Ping www.amazon.com three times**
1. What were the min/avg/max/stddev statistics for each?

> 1st: round-trip min/avg/max/stddev = 6.299/10.647/14.134/3.501 ms

> 2nd: round-trip min/avg/max/stddev = 5.271/34.017/133.779/50.002 ms

> 3rd: round-trip min/avg/max/stddev = 11.818/13.619/14.705/1.004 ms

2. Was there any packet loss on any of the pings?

> No, there wasn't any packet loss on any of the pings

3. Did the IP address change for a given website between pings?

> No IP address changes between pings

**Ping www.google.com three times**
1. What were the min/avg/max/stddev statistics for each?

> 1st: round-trip min/avg/max/stddev = 6.215/10.693/13.883/3.293 ms

> 2nd: round-trip min/avg/max/stddev = 5.370/10.442/13.900/3.149 ms

> 3rd: round-trip min/avg/max/stddev = 4.378/11.277/14.917/4.050 ms

2. Was there any packet loss on any of the pings?

> No, there wasn't any packet loss on any of the pings

3. Did the IP address change for a given website between pings?

> No IP address changes between pings

**Ping www.microsoft.com three times**
1. What were the min/avg/max/stddev statistics for each?

> 1st: round-trip min/avg/max/stddev = 5.952/11.231/14.335/2.970 ms

> 2nd: round-trip min/avg/max/stddev = 9.776/12.646/14.466/1.760 ms

> 3rd: round-trip min/avg/max/stddev = 5.347/12.906/18.095/4.154 ms

2. Was there any packet loss on any of the pings?

> No, there wasn't any packet loss on any of the pings

3. Did the IP address change for a given website between pings?

> No IP address changes between pings

## Using "tracert"
### Use tracert (or traceroute, depending on your OS) on the following sites:
1. www.google.com
- What was the target server's IP address?
> 142.250.217.68
- How many hops were needed to reach the target?
> 10 hops
- Can you identify your ISP from the intermediate server DNS names?
> I can't identify the ISP from the intermediate server DNS names
- Identify the "class" of IP address for each major step in the trip
> Step 1: 10.18.0.2 - Class A private IP address

> Step 2: 198.48.66.5 - Class C public IP address

> Step 3: 10.132.5.75 - Class A private IP address

> Step 4: 10.132.255.21 - Class A private IP address

> Step 5: 10.132.255.22 - Class A private IP address

> Step 6: 209.124.190.134 - Class C public IP address

> Step 7: 74.125.51.244 - Class A public IP address

> Step 9: 74.125.243.177 - Class A public IP address

> Step 10: 142.251.55.197 - Class B public IP address

2. www.amazon.com
- What was the target server's IP address?
> 18.65.233.187
- How many hops were needed to reach the target?
> 14 hops
- Can you identify your ISP from the intermediate server DNS names?
> I can't identify the ISP from the intermediate server DNS names
- Identify the "class" of IP address for each major step in the trip
> 10.18.0.2 - Class A public IP address

> 10.132.5.73 - Class A public IP address

> 10.132.5.75 - Class A public IP address

> 10.132.255.21 - Class A public IP address

> 10.132.255.22 - Class A public IP address

> 209.124.190.134 - Class C public IP address

> 209.124.181.245 - Class C public IP address

> 15.230.247.0 - Class A public IP address

> 18.172.169.208 - Class A public IP address

3. www.microsoft.com
- What was the target server's IP address?
> 23.216.81.152
- How many hops were needed to reach the target?
> 11 hops
- Can you identify your ISP from the intermediate server DNS names?
> No, the intermediate server DNS names do not provide enough information to identify the ISP.
- Identify the "class" of IP address for each major step in the trip
> irb--2523.uwir-ads-1.infra.washington.edu (10.18.0.2) - Private IP address (Class A private network)

> lo0--5.uwcr-atg-1.infra.washington.edu (198.48.66.5) - Public IP address (Class C public network)

> ae4--1009.uwcr-atg-1.infra.washington.edu (10.132.5.75) - Private IP address (Class A private network)

> wi_nat_int.uwcf-atg-2.infra.washington.edu (10.132.255.21) - Private IP address (Class A private network)

> et-8-0-0--4080.uwcr-atg-1.infra.washington.edu (10.132.255.22) - Private IP address (Class A private network)

> ae20--4010.icar-sttl1-3.infra.pnw-gigapop.net (209.124.188.134) - Public IP address (Class C public network)

> six-sea2.netarch.akamai.com (206.81.80.168) - Public IP address (Class C public network)

> a23-216-81-152.deploy.static.akamaitechnologies.com (23.216.81.152) - Public IP address (Class A public network)
