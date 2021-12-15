---
layout: post
title:  "Wireshark Analysis - Incident Response (FVTC)"
date:   2021-09-26 15:40:44 -0600
categories: incident-response fvtc
---
Assigned for my Incident Response course at Fox Valley Technical College, this project had me analyze a network capture PCAP file and produce an incident report. The PCAP file had about 4000 packets of traffic from a fictional organization that had been infected by a spyware Trojan called "*Agent Tesla*".

The deliverable for this project was an [incident report](/assets/wireshark-analysis/report.pdf) giving a summary of what happened. While performing my analysis, I had recorded my steps, notes, and thought process chronologically in another document, [my notes document](/assets/wireshark-analysis/notes.pdf), which was submitted alongside the incident report.

# Assignment Prompt

>Working with Wireshark: For this exercise we will collaborate to learn more Wireshark tools and see how we can analyze a PCAP file and artifacts from our IDS systems to produce an incident report.
>Look for the files in the folder \\Unit4 on your Kali Virtual Machine.  I included the incident report on purpose so we could validate our findings and apply it to our own incident report.
>
>Deliverables:
>  - Full Incident Response Report, you can use the form attached or your own formatting
>  - Screenshots with annotations
>  - The answer key is listed above, use it to validate your findings and also to catalog the details of the artifacts
>  - Identify each of the IR phases, when applicable.
>  - Include an executive summary at the beginning and a conclusion/lessons learned at the end
