Task 5: Capture and Analyze Network Traffic Using Wireshark

🎯 Objective

Capture live network packets and identify at least three basic network protocols using Wireshark on Windows.

🛠️ Tools Used

•Wireshark (Free and open-source network analyzer)
•Command Prompt (For ping commands)
•Web Browser (To generate HTTP traffic)

📋 Steps Followed:

	1.Installed Wireshar from the official site: [https://www.wireshark.org](https://www.wireshark.org)
	2.Started Wiresharkand selected the active network interface (Wi-Fi).
	3.Began capturing live packets by clicking the "Start" button.
	4.Generated network activity by:
	a.Visiting a website (https://example.com)
	b.Running `ping google.com` in Command Prompt
	5.Stopped the capture after about 1 minute.
	6.Filtered the traffic using Wireshark’s filter bar for the following protocols:
		a.`http`
		b.`dns`
		c.`icmp`
	7.Analyzed packets to understand communication and protocol use.
	8.Saved the capture as a `.pcap` file (`network_traffic.pcap`).

📊 Protocols Identified
	HTTP -
		-80, 443 
		-HyperText Transfer Protocol - Web page requests/responses
 
	DNS – 
		-53      
		-Domain Name System 
		-Resolves domain names to IPs 

	ICMP – 
		-Internet Control Message Protocol  
		-Used by `ping` to test reachability 

📁 Deliverables
	-network_traffic.pcap – The captured packet file.

📘 Outcome
	-Gained hands-on experience using Wireshark.
	-Learned how to capture and analyze live network traffic.
	-Identified key protocols used in common network activities.
	-Developed basic network protocol awareness.
