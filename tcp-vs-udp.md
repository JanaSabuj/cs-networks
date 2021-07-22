# TCP vs UDP

| TCP | UDP |
| :--- | :--- |
| It is a **connection oriented** protocol | It is a **connection less** protocol |
| Reliable as it provides **rigorous** **error checking support \(plus error recovery\)** and also **guarantees delivery** of messages to the receiver | Non-reliable because it does only **basic error checking with checksum \(no error recovery\)** and **no guarantee** of message delivery |
| It has **sequential** message transmission | **No sequential** messgae transmission |
| **Slow** delivery, less efficient | **Fast** delivery, more efficient |
| **Retransmission** supported in TCP, in case the packet gets lost or a need to resend | **No retransmission** facility |
| Used in heavy apps | Used for apps needing fast transmission - like games |
| One to One connection always present | Broadcast/Multicast |
| **3 way handshake** first established \(SYN - SYN/ACK - ACK\) | No 3 way handshake |
| **12 fields** in TCP packet | **4 fields** in UDP packet |
| Header size is 20 bytes | Header size is 8 bytes |
| HTTP, FTP, SMTP, TELNET | DNS, DHCP, VoIP |

