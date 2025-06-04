 TCP/HTTP Log Review – Wireshark Sample

This repo includes materials from a hands-on practice exercise involving packet capture review using Wireshark. The main focus was understanding how to read TCP/HTTP logs and recognize what normal vs. suspicious traffic looks like — specifically looking at signs of a SYN flood.

About the Project

Date:** May 2024  
Tools Used: Wireshark, TCP, HTTP  

This was a self-paced learning activity meant to build familiarity with how network traffic is logged and how to follow packet flows between devices. I used Wireshark to walk through a sample log and documented the steps involved in identifying both normal web traffic and traffic associated with a basic SYN flood denial-of-service scenario.

What's Included

- How-to-read-a-Wireshark-TCP_HTTP-log.docx**  
  A short guide I followed that explains how to interpret TCP handshake sequences, HTTP requests/responses, and what to look for when traffic gets abnormal.

- Wireshark TCP_HTTP log - TCP log.pdf**  
  A multi-page sample log showing a mix of clean and suspicious traffic. It includes examples of the handshake process, GET requests, server responses, and repeated SYN packets from a single IP (suggesting a SYN flood).

Why It Matters

Understanding packet-level activity is a big part of network security. This project helped me:
- Practice reading real logs from Wireshark
- Get comfortable with TCP behavior (like SYN, ACK, RST)
- See how DoS traffic patterns can show up in packet captures

Notes

This isn’t an advanced analysis or live lab — it’s a beginner-level breakdown and sample log walkthrough. Useful for anyone starting out in cybersecurity who wants to get better at reading logs and understanding how servers and clients talk to each other at the packet level.
