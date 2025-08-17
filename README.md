VPN Setup and Privacy

🌐 What this task was about

This task was about learning how a VPN (Virtual Private Network) works, setting one up, checking if it really hides our IP, and then understanding how it helps with privacy, encryption, tunneling protocols, and network security.

Basically, the goal was simple:

Install a free VPN → I used ProtonVPN.

Connect to a VPN server.

Check if my IP address changed.

Understand the benefits & limitations of VPNs.

---

🔑 Key Concepts

🔐 VPN (Virtual Private Network)

A VPN is like a private tunnel between my device and the internet. Normally, when we browse, our ISP (internet provider) and even hackers on the same WiFi can see what we’re doing. But with a VPN, the traffic goes through an encrypted tunnel, hiding both our real IP address and the websites we visit.

🛡️ Encryption

Encryption is the process of scrambling data so that no one can read it without the correct key. When a VPN is active, all the traffic from my system is encrypted using strong algorithms (like AES-256). This means:

Hackers can’t sniff my passwords over WiFi.

My ISP can’t track exactly which sites I’m visiting.

Even if someone intercepts the data, it’s just gibberish.


👤 Privacy

Privacy is the biggest reason people use VPNs. With a VPN:

My real IP address is hidden → replaced with the VPN server’s IP.

Websites can’t easily track my real location.

ISPs can’t build a complete history of what I do online.


⚠️ But VPNs don’t make me 100% anonymous. The VPN provider itself can still see traffic, which is why it’s important to use a trustworthy service.

🛣️ Tunneling Protocols

A VPN uses different protocols to create a secure tunnel. Some examples:

OpenVPN → Most common, secure, and open-source.

WireGuard → Newer, faster, lightweight, and secure.

IKEv2/IPSec → Good for mobile devices (handles switching between WiFi and data).


ProtonVPN uses OpenVPN and WireGuard, both considered strong and secure.

🌍 Network Security

From a security perspective, VPNs help protect against:

Man-in-the-Middle attacks on public WiFi.

Data snooping by ISPs.

Tracking & profiling by websites/advertisers.


However, VPNs do not protect from viruses or phishing, so it’s still important to use antivirus and browse carefully.


---

🛠️ What I did in this task

1. Checked my IP address before connecting using ifconfig.


2. Installed ProtonVPN on my system (sudo apt install proton-vpn-gnome-desktop).


3. Logged into ProtonVPN and connected to a server.


4. Ran ifconfig again → noticed a new interface called proton0 (proof that VPN is active).


5. My IP address changed after connecting, which confirmed that traffic was going through the VPN tunnel.


6. Browsed the internet while connected → everything worked, just slightly slower (as expected with free VPNs).




---

✅ Outcome

I successfully set up ProtonVPN and confirmed that my IP address was hidden.

Understood how VPNs encrypt traffic and protect privacy.

Learned about tunneling protocols and why they matter.

Realized VPNs are great for security, but they don’t make you completely invisible.
