# Currently none of this stuff actually works.

# dns-lists
Project on hold because some domains refuse to work with adguard and so now I put lancache-dns in front of adguard
Automate creating dns rewrite lists for [lancachenet](https://github.com/lancachenet/) using [cache-domains](https://github.com/uklans/cache-domains) and github actions.

## Instructions: Soon™

## Install:
just copy the raw url into pihole or adguard home

### Adguard: Doesn't work either due to the fact that Adguard doesn't accept DNS rewrites in list form and so just ignores it when it's an allow or deny list.
```https://raw.githubusercontent.com/Deanosim/dns-lists/main/adguard.txt```
### Pihole: (Pihole list currently doesn't work, and just blocks everything)
```https://github.com/Deanosim/dns-lists/raw/main/pihole.txt```
