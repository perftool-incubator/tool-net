# tool-net
record metrics from tc, netfilter, conntrack, ethtool

## iptables collection command
`iptables -nvxL`

## Conntrack collection command
`cat /proc/net/nf_conntrack`

## TC collection command
- `tc -j -s filter show dev dev_name ingress`
- `tc -j -s filter show dev dev_name egress`

This might change given nics and / or use of TC
