# Footprinting and Reconnaissance Using theHarvester

## Overview
A practical exercise using theHarvester 4.11.1 on Kali Linux to perform passive reconnaissance.

## Objective
To search for publicly indexed information associated with `microsoft.com`.

## Tools Used
- Kali Linux
- theHarvester 4.11.1

## Task 1: Baidu Search

Command:
```bash
theHarvester -d microsoft.com -l 100 -b baidu
```

**Results:** No emails, IP addresses, people or hosts were returned.

## Task 2: All Sources

Command:
```bash
theHarvester -d microsoft.com -l 50 -b all
```

**Results:** No people, emails, IP addresses or LinkedIn users were returned in the displayed results. At least one provider required an API key, limiting source coverage.

## Key Learning Outcomes
- Practised passive reconnaissance.
- Learned to specify a target domain, search source and result limit.
- Understood that missing API keys can limit search coverage.
- Learned to document findings and limitations accurately.

## Conclusion
This practical introduced theHarvester and demonstrated the importance of interpreting reconnaissance results carefully. Zero results do not prove that no publicly available information exists.
