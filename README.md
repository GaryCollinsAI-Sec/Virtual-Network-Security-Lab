

<h1>Virtual Network Security Lab</h1>
<p><strong>pfSense | VLANs | Wireshark | Suricata</strong></p>

<div class="section">
<h2>Overview</h2>
<p>
This project is a fully segmented virtual network security lab built using pfSense, VirtualBox, and multiple Linux environments. It simulates a real enterprise network with firewall enforcement, VLAN segmentation, and security testing workflows.
</p>

<div>
<span class="tag">Network Security</span>
<span class="tag">pfSense</span>
<span class="tag">VLANs</span>
<span class="tag">Penetration Testing</span>
<span class="tag">Virtualization</span>
</div>
</div>

<div class="section">



<div class="section">
<h2>📸 Lab Walkthrough (Setup → Completion)</h2>
<p>Full step-by-step build process with evidence.</p>
</div>

<div class="section">
<h2>🧱 Stage 1: Virtual Machine Deployment</h2>
<p>Virtual machines created in VirtualBox.</p>

<ul>
<li>pfSense Firewall</li>
<li>Ubuntu Workstation and target</li>
<li>Kali Linux Attacker</li>
<li>Metasploitable2 Target</li>
</ul>

<img width="726" height="368" alt="Screenshot From 2026-04-28 15-44-55" src="https://github.com/user-attachments/assets/ae4748f8-8973-4330-be07-d43baa743bf0" />
</div>

<div class="section">
<h2>🌐 Stage 2: Network Configuration</h2>
<p>Configured NAT and internal networks for isolation.</p>

<img width="1005" height="516" alt="Screenshot From 2026-04-28 15-46-01" src="https://github.com/user-attachments/assets/5a3a7be0-e326-47d0-b857-ddd9f5f23f68" />


<img width="1005" height="516" alt="Screenshot From 2026-04-28 15-50-18" src="https://github.com/user-attachments/assets/8cd4481d-6835-48d0-897a-0c41af20705c" />


</div>

<div class="section">
<h2>⚙️ Stage 3: pfSense Installation</h2>
<p>Installed and configured firewall routing and DHCP.</p>

<img width="723" height="459" alt="Screenshot From 2026-04-25 11-26-15" src="https://github.com/user-attachments/assets/a979b6d4-c7b1-42a2-badd-52d798a93a14" />
" alt="pfSense Dashboard">
</div>



<div class="section">
<h2>🧪 Stage 4: Security Testing</h2>
<p> Kali Linux Nmap scan on metasploitable 2.</p>

<img width="649" height="515" alt="Screenshot From 2026-04-25 23-06-39" src="https://github.com/user-attachments/assets/bd00e572-89fe-421a-a0fc-73013d6af070" />

</div>


<div class="section">
<h2>🧪 Stage 5: Packet Capture</h2>
<p>Once the nmap scan was done from kali unto the ubuntu I was able to capture network packets using wireshark.</p>

<img width="860" height="311" alt="Screenshot From 2026-04-25 23-29-51" src="https://github.com/user-attachments/assets/5226c586-f888-4db3-a3bc-d9f9def534df" />

</div>


<div class="section">
<h2>🧪 Stage 6: Surricata</h2>
<p> Capture log alert using suricata from the pfsense web ui using Kali Linux and Nmap scans to target metasploitable 2.</p>

<img width="1142" height="387" alt="Screenshot From 2026-04-25 23-08-32" src="https://github.com/user-attachments/assets/4d0fd23c-a667-408a-bc61-cd2cd75cbbb9" />

</div>


<div class="section">
<h2>🔥 Stage 7: Firewall Rules</h2>
<p>Configured default deny policy and controlled access rules to both metasploitable 2 and ubuntu virtual machines.</p>

<img width="1203" height="684" alt="Screenshot From 2026-04-29 21-15-40" src="https://github.com/user-attachments/assets/201b05c8-2704-463a-b681-f381d93bd475" />


<p>I tested the firewall rule by simulated the attack on my ubuntu virtual machine using kali and it successfully blocked it once implemented the rules.</p>

  <img width="656" height="518" alt="Screenshot From 2026-04-29 21-19-57" src="https://github.com/user-attachments/assets/473ea044-3457-4b08-ab4d-35356f92e02a" />




</div>



<div class="section">
<h2>🧩 Stage 8: VLAN Segmentation & DHCP Server</h2>
<p>Implemented VLAN isolation between users and servers.</p>

<img width="1184" height="565" alt="edited vlan (Edited)" src="https://github.com/user-attachments/assets/c1e44631-8bc9-4e1e-bb5f-56d33def7268" />


<p>Implemented a DHCP server for each interface of VLAN that is assigned.</p>

<img width="1187" height="489" alt="DHCPserver" src="https://github.com/user-attachments/assets/6f340a34-1ca1-46e5-be64-498ff7630dad" />



</div>


<div class="section">
<h2>🏁 Stage 9: Final Lab State</h2>
<p>Fully functional segmented network with validated controls.</p>


<img width="722" height="458" alt="Screenshot From 2026-04-29 22-46-14" src="https://github.com/user-attachments/assets/855172c9-ea6d-4a0b-b969-90680d6bc9c7" />


</div>

<div class="section">
<h2>🧠 Skills Demonstrated</h2>

<ul>
<li>Firewall Configuration (pfSense)</li>
<li>VLAN Segmentation</li>
<li>Penetration Testing</li>
<li>Traffic Analysis</li>
<li>Security Validation</li>
</ul>
</div>

<div class="section">


<div class="section">
<h2>📈 Future Improvements</h2>
<ul>
<li>Integrate SIEM (Wazuh / Splunk)</li>
<li>Automate firewall rules</li>
<li>Add Active Directory</li>
</ul>
</div>

<div class="section">
<h2>🏁 Conclusion</h2>
<p>
This project demonstrates a fully segmented and secured virtual network environment combining defensive and offensive security techniques. It reflects real-world enterprise concepts such as least privilege, network segmentation, and firewall enforcement.
</p>
</div>

</div>
</body>
</html>
