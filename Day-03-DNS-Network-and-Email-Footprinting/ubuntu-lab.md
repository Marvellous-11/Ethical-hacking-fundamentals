<img width="641" height="157" alt="Screenshot 2026-08-06 125649" src="https://github.com/user-attachments/assets/fd97489e-531e-40c3-98c8-cefe30ed1770" />


ping google.com is a network diagnostic command that checks whether your computer can reach the host google.com and measures how long it takes for packets to travel there and back.


<img width="638" height="104" alt="Screenshot 2026-08-06 125753" src="https://github.com/user-attachments/assets/6cf712dc-86e3-4e8f-baae-27f67213fb0e" />



nslookup google.com is a command used to query the Domain Name System (DNS). It asks a DNS server, "What IP address belongs to google.com?"

Unlike ping, nslookup does not test whether the server is reachable. It only checks whether the domain name can be resolved to an IP address (and can also retrieve other DNS records).



<img width="638" height="219" alt="Screenshot 2026-08-06 125836" src="https://github.com/user-attachments/assets/3f454255-b581-49f6-acca-56a9e961cd15" />



dig google.com stands for Domain Information Groper. It is a powerful DNS lookup tool used to query DNS servers and retrieve detailed information about a domain.

Like nslookup, dig does not test connectivity. It only queries DNS.



<img width="632" height="183" alt="Screenshot 2026-08-06 125915" src="https://github.com/user-attachments/assets/d29ab905-2e36-4958-ac1f-b3d1978a8a07" />



dig google.com MX queries the MX (Mail Exchange) DNS records for google.com.

An MX record tells the internet which mail servers are responsible for receiving email for a domain.



<img width="627" height="249" alt="Screenshot 2026-08-06 125956" src="https://github.com/user-attachments/assets/ea4ba9d7-3516-4726-a5db-62d9f7a5e4c3" />



dig google.com NS queries the NS (Name Server) DNS records for google.com.

Name Servers are the DNS servers that are authoritative for a domain. They store or direct queries to the official DNS records for that domain.




<img width="632" height="206" alt="Screenshot 2026-08-06 130051" src="https://github.com/user-attachments/assets/29c2470b-59f6-4eac-97d8-c2e0f39fcad1" />




dig google.com TXT queries the TXT (Text) DNS records for google.com.

A TXT record stores text information associated with a domain. While it can contain any text, it is commonly used for email security, domain verification, and other configuration data.



<img width="635" height="45" alt="Screenshot 2026-08-06 130136" src="https://github.com/user-attachments/assets/9c8dfbe0-1146-40e0-85f7-a366da06fe51" />



traceroute google.com shows the path that network packets take from your computer to Google's servers.

Instead of simply telling you whether Google is reachable (like ping), it shows each router (hop) the packets pass through on the way to the destination.
