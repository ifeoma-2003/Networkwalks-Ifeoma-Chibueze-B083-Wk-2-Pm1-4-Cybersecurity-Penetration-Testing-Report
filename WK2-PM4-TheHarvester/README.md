## PM4 - TheHarvester

Networkwalks Cybersecurity Internship | B083 | Week 2

## Practical Overview

TheHarvester is an open-source reconnaissance tool used to collect publicly available information associated with a target domain.
This practical focused on using TheHarvester to examine the publicly observable footprint of microsoft.com, including information such as:
```
Email addresses
Hostnames
IP addresses
Domain related intelligence returned by available sources.
```

## Practical Objectives

The practical was undertaken to:
```
Understand the purpose of automated OSINT collection.
Examine publicly available information associated with a domain.
Compare reconnaissance results obtained from different search purposes.
Develop familiarity with TheHarvester's domain, result limit, and source selection options.
Document reconnaissance findings responsibly.
```

## Command & Methodology

## Command 1-Baidu-Based Reconnaissance
```
theHarvester -d microsoft.com -l 1000 -b
```
## Parameters:
```
-d: Specifies the target domain.
-l 1000: Sets the result limit to 1,000.
-b baidu: Specifies Baidu as the information source.
```

This command was used to examine the domain using a defined search source and a higher result limit.


## Command 2-multi-source Reconnaissance
```
theHarvester -d microsoft.com -l 50 -b all
```
## Parameters:
```
-d: Specifies the target domain.
-l 50: Sets the result limit to 50.
-b all: Requests collection from all supported available sources.
```

This provided a broader reconnaissance approach for identifying publicly available domain related information.


## Reconnaissance Findings

TheHarvester's output was examined for publicly available intelligence associated with the target domain, including:
```
Email addresses
Hostnames
IP addresses
Names/people, where returned
Source information
Other domain related results reported by the tool.
```

The results from the two commands provide an opportunity to observe how the selected source and result limi can influence the information returned during automated reconnaissance.


## Evidence & Documentation

![](https://github.com/ifeoma-2003/Networkwalks-Ifeoma-Chibueze-B083-Wk-2-Pm1-4-Cybersecurity-Penetration-Testing-Report/blob/main/THE%20HARVESTER.png)

![](https://github.com/ifeoma-2003/Networkwalks-Ifeoma-Chibueze-B083-Wk-2-Pm1-4-Cybersecurity-Penetration-Testing-Report/blob/main/THE%20HARVESTER%202.png)

![](https://github.com/ifeoma-2003/Networkwalks-Ifeoma-Chibueze-B083-Wk-2-Pm1-4-Cybersecurity-Penetration-Testing-Report/blob/main/THE%20HARVESTER%203.png)

## Skills Developed
```
Passive reconnaissance
OSINT collection
Domain intelligence gathering
Automated information discovery
Source comparison
Command line reconnaissance
Security focused documentation
```

The practical reinforced how publicly available information can be systematically collected and organized to develop an initial picture of a target's external digital footprint.


## Ethical Practice & Professional Principle

TheHarvester should be used only within an authorized scope. Public availability of information does not automatically authorize further access, exploitation, or interaction with associated systems.
This practical was conducted for cybersecurity training, with emphasis on passive reconnaissance , information analysis, and responsible documentation.

## Tools

## TheHarvester

TheHarvester was executed within Kali Linux to perform automated passive reconnaissance against the specified domain.

## Author

Chibueze Ifeoma | Networkwalks Cybersecurity Internship | B083 | Week 2
