## PM1-Footprinting
```
Networkwalks Cybersecurity Internship | Batch B083|Week 2
Practical Module 1: Footprinting & Reconnaisance 

```
## Practical Context

Footprinting represents the information gathering foundation of a penetration testing engagement. Before attempting
to assess the security of a target, a security practitioner must first establish an informed understanding of the 
target's externally observable presence.
This practical explored the principles behind footprinting and the systematic collection of information that may contribute 
to a target profile. Rather than treating reconnaissance as the simple retrieval of isolated data, the exercise approached
it as a process of identification, correlation, interpretation, and documentation.

## Purpose Of The Exercise

The purpose of this practical was to develop a practical understanding of how reconnaissance contributes to the broader
penetration testing process.
The exercise was designed to:
```
1) Examine the concept and purpose of footprinting.
2) Identify information that may be obtainable through publicly accessible sources.
3) Understand how individual findings can contribute to a broader target profile.
4) Develop a structured approach to reconnaissance and information documentation.
5) Examine the relationship between publicly exposed information and an organization's external attack surface.

```

## Reconnaissance Approach

The practical followed a reconnaissance-oriented approach in which available information was examined before considering 
any deeper technical assessment.
The process can be represented as:
```
Target Identification
Information Collection
Correlation
Interpretation
Documentation

```

This approach is important because reconnaissance is not simply about collecting as much information as possible. The value of a finding depends on its relevance, reliability, and relationship to other information associated with the target.

## Information Gathering Process

1) ## Establishing the Target Profile

The first stage involved establishing the identity and context of the target being examined. This provided a reference point against which subsequent information could be considered.

2) ## Identifying Publicly Available Information

Attention was the directed towards information that could be obtained through publicly accessible sources. This demonstrated how a target's digital presence may reveal useful information without requiring direct access to restricted systems.

3) ## Correlating Findings

Individual findings were considered in relation to one another rather than in isolation. Correlation is an important aspect of reconnaissance because separate pieces of information may collectively provide greater insight into a target's 
external presence.

4) ## Documenting Observations 

Relevant observations were recorded as part of practical documentation process. Proper documentation ensure that reconnaissance findings can be reviewed, interpreted, and referenced during subsequent stages of the security assessment.

## Observations & Analysis

The practical demonstrated that an organization's digital footprint can extend beyond the information it intentionally presents.
Several observations emerged from the exercise:
```
Publicly accessible information can provide useful reconnaissance context.
Information obtained from different sources may become more meaningful when correlated.
Reconnaissance can help establish an initial understanding of a target's externally visible presence.
The presence of information does not, by itself, constitute a vulnerability; its security significance requires contextual analysis.
Systematic documentation is essential for transforming raw reconnaissance data into useful security information.
```
The exercise therefore highlighted the distinction between information discovery and security analysis. Identifying information is only the beginning; Understanding what the information means within the context of the target is equally important.

## Security Significance

From a security perspective, footprinting provides an opportunity to understand what information about an organization may be externally observable.
An extensive or poorly controlled digital footprint may provide useful reconnaissance material to an unauthorized actor. Consequently, organizations benefit from maintaining awareness of publicly exposed information and periodically reviewing whether such exposure is necessary.
For a penetration tester, footprinting establishes the context required to approach subsequent assessment activities in a more informed and structured manner.

## Evidence & Documentation



## Skills & Competencies Developed

This practical strengthened my understanding of:
```
1) Reconnaissance methodology
2) Information gathering
3) Target profiling
4) OSINT principles
5) Information correlation
6) Attack surface awareness
7) Security focused documentation
8) Analytical interpretation of reconnaissance findings

```
More importantly, the exercise shifted my understanding of reconnaissance from simply finding information to understanding how information can be structured, correlated, and interpreted within a security context.

## Professional & Ethical Responsibility

Footprinting techniques must be applied within a clearly defined and authorized scope.
Although publicly accessible information can be collected without bypassing technical controls, responsible cybersecurity practice requires practitioners to respect authorization boundaries , applicable laws, organizational policies, and the intended purpose of an assessment.
The activities documented in this repository were conducted as part of cybersecurity training. Findings obtained during an assessment should be handled responsibly and should not be used to access, disrupt, or compromise systems without explicit authorization.

## Tools Used

The footprinting exercise was conducted within Kali Linux using a combination of reconnaissance and information gathering utilities. Each tool was used for a specific aspect of understanding the publicly observable characteristics of the target domain.

1) ## WHOIS

Command:
```
whois networkwalks.com

Used to retrieve publicly available domain registration and administrative information associated with the target domain.
```

2) ## WhatWeb

Command:
```
whatweb networkwalks.com

Used to identify technologies, webserver information, and other detectable characteristics associated with the target website.
```

3) ## NSLookup

Command:
```
nslookup networkwalks.com

Used to query DNS information and examine the domain's DNS resolution.
```

4) ## cURL

Command:
```
curl -I https://networkwalks.com

Used to retrieve the HTTP response headers returned by the target website and examine information exposed through the web server's response.
```

5) ## Wafwoof

Command:
```
wafw00f networkwalks.com

Used to determine whether a Web Application Firewall (WAF) could be detected protecting the target website.
```

6) ## DNSRecon

Command:
```
dnsrecon -d networkwalks.com

Used to perform DNS reconnaissance against the target domain and identify available DNS related information
```

## Author 

Chibueze ifeoma | Networkwalks Cybersecurity Internship | B083 | Week 2
