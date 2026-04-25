

<h1>Virtual Network Security Lab</h1>
<p><strong>pfSense | VLANs | VPN</strong></p>

<div class="section">
<h2>Overview</h2>
<p>
This project is a fully segmented virtual network security lab built using pfSense, VirtualBox, and multiple Linux environments. It simulates a real enterprise network with firewall enforcement, VLAN segmentation, VPN access, and security testing workflows.
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
<h2>🧱 Architecture</h2>


<div class="section">
<h2>📸 Lab Walkthrough (Setup → Completion)</h2>
<p>Full step-by-step build process with evidence.</p>
</div>

<div class="section">
<h2>🧱 Stage 1: Virtual Machine Deployment</h2>
<p>Virtual machines created in VirtualBox.</p>

<ul>
<li>pfSense Firewall</li>
<li>Ubuntu Workstation</li>
<li>Kali Linux Attacker</li>
<li>Metasploitable2 Target</li>
</ul>

<img src="images/01-vm-setup.png" alt="VM Setup">
</div>

<div class="section">
<h2>🌐 Stage 2: Network Configuration</h2>
<p>Configured NAT and internal networks for isolation.</p>

<img src="images/02-network-config.png" alt="Network Config">
</div>

<div class="section">
<h2>⚙️ Stage 3: pfSense Installation</h2>
<p>Installed and configured firewall routing and DHCP.</p>

<img src="images/03-dashboard.png" alt="pfSense Dashboard">
</div>

<div class="section">
<h2>🧩 Stage 4: VLAN Segmentation</h2>
<p>Implemented VLAN isolation between users and servers.</p>

<ul>
<li>VLAN 10 → Users</li>
<li>VLAN 20 → Servers</li>
</ul>

<img src="images/04-vlan.png" alt="VLAN Config">
</div>

<div class="section">
<h2>🔥 Stage 5: Firewall Rules</h2>
<p>Configured default deny policy and controlled access rules.</p>

<img src="images/05-firewall-rules.png" alt="Firewall Rules">
</div>

<div class="section">
<h2>🧪 Stage 6: Security Testing</h2>
<p>Validated segmentation using Kali Linux and Nmap scans.</p>

<img src="images/06-nmap.png" alt="Nmap Scan">
</div>

<div class="section">
<h2>🔐 Stage 7: VPN Access</h2>
<p>Configured secure remote access into lab environment.</p>

<img src="images/07-vpn.png" alt="VPN">
</div>

<div class="section">
<h2>🏁 Stage 8: Final Lab State</h2>
<p>Fully functional segmented network with validated controls.</p>

<img src="images/08-final-lab.png" alt="Final Lab">
</div>

<div class="section">
<h2>🧠 Skills Demonstrated</h2>

<ul>
<li>Network Architecture Design</li>
<li>Firewall Configuration (pfSense)</li>
<li>VLAN Segmentation</li>
<li>Penetration Testing</li>
<li>Traffic Analysis</li>
<li>Security Validation</li>
</ul>
</div>

<div class="section">
<h2>⚠️ Challenges & Solutions</h2>

<table>
<tr>
<th>Challenge</th>
<th>Solution</th>
</tr>
<tr>
<td>pfSense storage issue</td>
<td>Added SATA controller and reattached disk</td>
</tr>
<tr>
<td>Boot failure</td>
<td>Fixed ISO boot order</td>
</tr>
<tr>
<td>No DHCP</td>
<td>Enabled DHCP on LAN/VLAN</td>
</tr>
<tr>
<td>Interface misconfig</td>
<td>Reassigned WAN/LAN manually</td>
</tr>
</table>
</div>

<div class="section">
<h2>📈 Future Improvements</h2>
<ul>
<li>Deploy IDS/IPS (Suricata / Snort)</li>
<li>Integrate SIEM (Wazuh / Splunk)</li>
<li>Automate firewall rules</li>
<li>Add Active Directory</li>
<li>Simulate lateral movement attacks</li>
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
