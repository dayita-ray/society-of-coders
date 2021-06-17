title: 'Packets'
date: '06-16-2021'
class: 'CSP' # CSA or CSP
section: 1 # A number to represent Unit or Big Idea (optional for pbl)
keywords: 'TCP< UDP' # Keywords to describe your project seperated by commas
tech: 'corrupted, lost, out-of-order # What you used (Language, frameworks, Database) seperated by commas (only for pbl)
author: 'Dayita Ray' # Optional
authorLink: 'https://github.com/dayita-ray' # Optional '

Packets can be corrupted, which means that for some reason, the received data no longer matches the originally sent data.
Packets can be lost due to problems in the physical layer or in routers' forwarding tables. If even one packet of a message is lost, it may be impossible to put the message back together in a way that makes sense.
Similarly, packets might be duplicated due to accidental retransmission of the same packet.
Transmission Control Protocol (TCP) is the data transport protocol that's most commonly used on top of IP and it includes strategies for packet ordering, retransmission, and data integrity.
TCP includes mechanisms to solve many of the problems that arise from packet-based messaging, such as lost packets, out of order packets, duplicate packets, and corrupted packets.
User Datagram Protocol (UDP) is an alternative protocol that solves fewer problems but offers faster data transport.
UDP provides a mechanism to detect corrupt data in packets, but it does not attempt to solve other problems that arise with packets, such as lost or out of order packets. That's why UDP is sometimes known as the Unreliable Data Protocol.

Practice Problem FRQ: What is “better”, TCP or UDP and make a justification and argument for your answer. Include complexity.

Same Response: TCP is “better” because both attempt to detect corrupt data in packets, however TCP also attempts to solve other problems such as packet ordering, retransmission, and data integrity. However, UDP does offer faster data transport.
