# small-business-network
In this lab, we are going to set up a template of a typical small business network.

Draft notes:
   1. The business (Noit Resources) will have a mix of wired desktops, printer/copy machine, a file server and laptops (wired).
   2. They will use a router, firewall and switches.
   3. The office network will be segregated into several VLANs for each department.
   4. The departments in the network
      1. CEO Office 
      2. Accounts
      3. Sales 
      4. Marketing
      5. IT
      6. Human Resource
   5.
   6. VLAN assignments
      1.  VLAN 10 SALES
      2.  VLAN 20 MARKETING
      3.  VLAN 30 HR
      4.  VLAN 40 ACC
      5.  VLAN 50 SERVERS
      6.  VLAN 60 CEO's Office
      7.  VLAN 70 IT
      8.  VLAN 90 (IOT) - Printers etc
   7. Security:
      1.   All unused ports are disabled/secured
      2.   All open ports are tied to device MAC address
   8.Configuration
      1. Router
         1. Secure router
         2. VLAN set up
         3. ACL/routing
         4. Port configuration (trunk/access)
      2. Set up individual devices (PC, printers)
      3. Allow employee to remote access own workstations at office? - Under discussion
      4. Firewall setup

Staff documentation
   1. Procedures - system info, login, procedures
   2. 
Future upgrade
1. electronic attendance
2. CCTV
3. Cloud
