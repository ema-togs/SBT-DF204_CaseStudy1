# SBT-DF204 Case Study 1: Nitroba Digital Forensics Investigation

## Overview
This repository contains the forensic evidence log, timeline analysis, and final conclusion report for **SBT-DF204 Case Study 1**. The investigation involved analyzing packet capture data (`nitroba.pcap`) to trace a harassing web communication sent to Chemistry 109 instructor Lily Tuckrige back to its originating device and enrolled student.

## Key Findings
* **Target:** Lily Tuckrige (`lilytuckrige@yahoo.com`)
* **Incident Payload:** HTTP POST submission to `willselfdestruct.com` (Packet `83601`, TCP Stream `1707`)
* **Timestamp:** `2008-07-22 02:04:24 EDT` (`06:04:24 UTC`)
* **Attributed IP Address:** `192.168.15.4`
* **Attributed MAC Address:** `00:17:f2:e2:c0:ce`
* **User Identity:** `jcoachj@gmail.com` (correlated via HTTP session cookies in Packets `77528`, `78967`, and `79012`)
* **Subject:** **Johnny Coach** (Chemistry 109 student)

## Repository Structure

SBT-DF204_CaseStudy1/
├── reports/            # Formatted text reports, timestamps, and evidence log
├── working/            # Working artifacts and extracted text data
└── case_materials/     # Investigation scenarios and supporting materials
