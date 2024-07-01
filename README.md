1. Primary Objective

The primary objective of this project is to develop a comprehensive cloud strategy for BookShow, one of the leading online ticketing platforms. BookShow currently manages its IT infrastructure, including hardware, software, and on-site. Our approach aims to transition from the current on-premises model to a cloud-based solution to enhance operational efficiency and overall business performance. To help drive this transformation, we will outline a detailed cloud strategy and a sample deployment plan.

2. Background of the Enterprise
BookShow is a prominent entertainment company known for its leading Online Ticketing Platform, catering to various events including movies, plays, concerts, and sporting events. In addition to ticketing, BookShow offers an online media streaming service and comprehensive management solutions for both virtual and on-ground entertainment experiences, covering all genres. The core operation of BookShow revolves around its online platform, which facilitates the booking of tickets for various entertainment events, with a primary focus on movies.
 
2.1 Size of the Business
BookShow is a medium-sized enterprise with a total of approximately 33 employees. The workforce is structured as follows:

IT Management:
  - 2 IT Managers

Network and Systems Administration:
  - 2 Network Administrators
  - 4 Systems Administrators

Development Team:
  - 4 Backend Developers
  - 4 Frontend Developers

IT Support and Maintenance:
  - 3 IT Support Specialists
  - 4 Help Desk Technicians

Cloud and Database Management:
  - 1 Cloud Engineer
  - 2 Cloud Solutions Architects
  - 2 Database Administrators

Project and Security Management:
  - 1 Scrum Master
  - 3 Security Specialists
  - 1 IT Project Manager
    
3. Current IT setup 
Let's delve into the detailed IT infrastructure of BookShow, covering aspects of hardware, software, and on-site management.

3.1 Hardware
 
On-premises Servers:
BookShow’s IT infrastructure includes several key components. The web servers host the website and application, handling user inquiries, ticket bookings, and providing web content, typically using software like Apache and Nginx (Nginx, n.d.; Apache HTTP Server Project, n.d.). The database servers are dedicated to storing and managing transactional data, customer information, and event details, utilizing relational database management systems like SQL Server or PostgreSQL (Microsoft SQL Server, n.d.; PostgreSQL, n.d.). Media servers are employed for streaming media content and storing large media files. Backup servers ensure critical data backup and data availability during power outages. In addition to other features, hardware load balancers are utilized to ensure that web traffic is evenly distributed to web servers, resulting in high availability and reliability.

3.2 Software

Operating Systems:
The operating systems primarily used are Linux servers, such as Ubuntu and CentOS, chosen for their reliability and security, and deployed across web, database, and media servers. BookShow utilizes several key applications and services to ensure smooth operations. A custom ticketing platform is specialized software that manages ticket bookings, user profiles, financial transactions, and event organization. CRM (Customer Relationship Management) will manage interactions with customers, sales, and support (ProInfluent, n.d.). Content management system 'CMS', manages website content management, promotions, and advertising (Kinsta, n.d.). Integration of APIs and services with multiple payment gateways to support online transactions. Additionally, Server health and performance are monitored using monitoring tools like Nagios and Zabbix (Nagios, n.d.; Zabbix, n.d.).

3.3 Internet Connectivity and Network Hardware

BookShow ensures robust internet connectivity with high-bandwidth connections to handle large volumes of user traffic. Additionally, switches and routers are employed to maintain seamless internal and external network connectivity.

3.4 Security Components

BookShow implements a range of security measures to secure its infrastructure. A hardware firewall is implemented to safeguard the system from external cyber threats, while a software firewall is employed to defend the network from unauthorized access. Network traffic is monitored by an intrusion detection system “IDS” and an “intrusion prevention system” IPS to detect suspicious activity and prevent potential attacks (Okta, n.d.). Additionally, measures are taken to mitigate the impact of Distributed Denial of Service (DDoS) attacks to ensure continuous service availability.

3.5 Power and Cooling

BookShow uses an UPS as a backup power, to ensure the server remains functional during a power outage. Additionally, a cooling system is applied to maintain optimal operating temperatures for servers and network devices. 
