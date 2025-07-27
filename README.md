# Wireshark-Traffic-Analysis-Lab
Tools Used:
• Wireshark on macOS
Safari and macOS terminal commands (e.g., `ping`)
Summary

I captured live traffic on my MacBook while:
Visiting a basic HTTP site (`http://neverssl.com`)
Visiting a secure HTTPS site (`https://example.com`)
Running a ping command to Google's DNS
Filters Used

 Filter: Purpose                      `http` Capture plaintext HTTP traffic 
`tls`  Show encrypted TLS sessions    
`icmp` Show ping (ICMP echo) packets  
`dns`  Display DNS queries/responses 

Screenshot
The included screenshot has been edited to blur:
IPv6 and IPv4 addresses
MAC addresses
Hostnames and User-Agent strings

Key Takeaways
DNS queries can expose domain names even over HTTPS
TLS handshakes don’t reveal content, but show the server
ICMP packets are useful for diagnosing network reachability

Privacy & Ethics

No private or sensitive data is included in the screenshot. This lab was performed in a home lab environment for educational purposes only.




