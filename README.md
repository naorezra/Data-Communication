# Data-Communication

<b>Copyright © Naor Ezra No copying, editing or use of the code.

This code is shown only for job search purposes.</b>

<b>Data Communication Semester Project - Using Cisco Packet Tracer</b>

General guidelines and definitions:
1. A high-tech company called "Engineers45" has 5 branches around the world: Haifa, Los Angeles,
Alexandria, Milan, London.
2. The Haifa branch is considered the main branch of the company.
third. 
3.A communication network must be designed and built with a WAN infrastructure that will enable the connection of local LAN networks
Of all branches in the company.
4. Each branch will be able to communicate with all the other branches and will be able to share vital information with the other branches.
God. 
5.Each branch has a local area network LAN and computer equipment as described in the following table.
and. 
6.The Haifa branch has an HTTPS server that provides a surfing service to the company's website.
7. The Alexandria branch houses the DNS server and the DHCP server.
8. The company has an intranet site (internal organizational Internet), the site pages are stored on the company's server.


General requirements:
1. Full planning and documentation must be submitted to the networks in an Excel file separately, which includes, among other things, a full summary.
Describing the network structure and project objectives, design tables of all IP addresses for each
The interfaces interfaces of the routers, including any other relevant information for the project) see examples
Attached (.) Write in the simulation file the names of the couple, including the ID number of each one individually
2. At the end of the work and after checking the integrity and success of the project, text files of settings must be submitted
All 5 routers in all branches and the SWITCH switch settings of the Los Angeles branch only) set with
VLAN, (Each file must be given a suitable name, a total of 6 files.
) This can be done through: Export to Configuration-Startup of NVRAM memory content.)

3. The company's branches will be interconnected in a WAN infrastructure that integrates fiber optic lines in the connection
Mesh fabric at least) Full fabric is better (to ensure network survival) see attached drawing (.
4. It is mandatory to document the structure of the logical network on the drawing itself in the overall simulation program, including:
The names of the routers, switches, computers, servers, communication lines, IP addresses including M.S
And DNS, DG and bandwidth addresses of the infrastructure. The drawing must be legible and understandable.
5. Each student will plan and determine the IP addresses of the WAN network as he wishes, all the addresses will be addresses
public .
6. The LAN addresses of the stations, printers and servers will be determined at the branches according to the table given above.
And statically excluding the Alexandria branch.
7. In the Alexandria branch the DNS server will also be used as a DHCP server for positions in the branch only, ie to activate
DNS service and also DHCP service on the same server (same computer)

In routers:
All branches should use the EIGRP dynamic routing protocol only) Do not use
RIP,) Also a different Width Bandwidth must be determined in each communication line separately, recorded and documented
On the communication lines in the drawing and the BW value, write for example: 2Mbps = BW


