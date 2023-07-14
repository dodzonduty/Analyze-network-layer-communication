# Analyze-network-layer-communication
<h2>Description</h2>
In this project, I'm a cybersecurity analyst working at a company that specializes in providing IT consultant services. Several customers contacted the company to report that they were not able to access the company website www.yummyrecipesforme.com, and saw the error “destination port unreachable” after waiting for the page to load. I'm tasked with analyzing the situation and determining which network protocol was affected during this incident.
<h2>Project processes</h2>
 To start, I visited the website and also received the error “destination port unreachable.” I loaded a network analyzer tool and tried to access the webpage again. This time, I recieved a lot of packets in the network analyzer. The analyzer shows that when you send UDP packets and receive an ICMP response returned to your host, the results contain an error message: “udp port 53 unreachable.”<br>
 <a href="DNS & ICMP traffic log.pdf">DNS&ICMP traffic logs</a><br>
 after analyzing the logs it was time to identify which network protocol and service were impacted by this incident and write a follow-up report.
 <a href="Cybersecurity incident report network traffic analysis.pdf">Follow-up report</a>
 
 
