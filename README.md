<h1>Microsoft Azure Sentinal (SIEM) with Virtual Machine (Honeypot)</h1>

<h2>Description</h2>
Azure Sentinel (SIEM) setup along with a live Virtual Machine acting as a Honey Pot. Will observe live attacks (RDP Brute Force) from around the world. Will use a custom PowerShell script to look up attacker's Geolocation information and plot it on the Azure Sentinel Map.
<br />


<h2>Utilities Used</h2>

- <b> Microsoft Azure
  - Create Azure Subscription
  - Create Virtual Machine
  - Allow “all” (*) in Firewall
  - Create Log Analytics Workspace
  - Enable gathering VM logs in Security Center
  - Connect Log Analytics to VM
  - Setup Azure Sentinel
  - Log into VM with Remote Desktop
  - Observe Event Viewer Logs in VM
  - Turn off Windows Firewall on VM
  - Download PowerShell Script
  - Get Geolocation.io API Key
  - Run Script To get Geo Data from attackers
  - Create custom log in LAW to bring in our custom log
  - Create custom fields/extract fields from raw custom log data
  - Testing Extracts
  - Setup map in sentinel with Latitude and Longitude (or country)
  - Fixing Map plot sizes 
