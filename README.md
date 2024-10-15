## 🌐 Company Branch Network Implementation Project

This Company Branch Network Implementation Project is a semester project developed as part of the networking curriculum. It demonstrates the application of network design principles and practical skills acquired during the course.

XYZ Company, a fast-growing organization based in Eastern Australia, is expanding its operations by establishing a new branch in Bonalbo. The goal of this project is to design a separate, efficient, and secure network infrastructure to support the company's new location, applying industry standards and best practices.

This project focuses on configuring VLANs, DHCP, and inter-VLAN communication to create a scalable and robust network infrastructure, aligning with the academic requirements and real-world scenarios encountered in professional IT environments.


## 📋 Table of Contents
- Project Overview
- Objectives
- Network Design
- Implementation Details
- Security Measures
- Network Diagram
- Screenshots
- Contributing
- License
- Contact

## 📘 Project Overview
XYZ Company is expanding its operations by establishing a new branch in Bonalbo, Eastern Australia. 
This project aims to design a separate, efficient, and secure network infrastructure to support their new location.

## 🎯 Objectives
- Design a network infrastructure for the Bonalbo branch with 3 department-specific VLANs.
- Provide wireless connectivity for each department.
- Enable automatic IP addressing for all devices using DHCP.
- Ensure inter-department communication through proper routing.

## 🖥️ Network Design
Subnet Allocation

Admin/IT Department:
   - Network ID: 192.168.1.0/26
   - Broadcast Address: 192.168.1.63
   - Usable Host Range: 192.168.1.1 - 192.168.1.62

Finance/HR Department:
   - Network ID: 192.168.1.64/26
   - Broadcast Address: 192.168.1.127
   - Usable Host Range: 192.168.1.65 - 192.168.1.126

Customer Service/Reception Department:
   - Network ID: 192.168.1.128/26
   - Broadcast Address: 192.168.1.191
   - Usable Host Range: 192.168.1.129 - 192.168.1.190
     
## ⚙️ Implementation Details
Router Configuration

- Inter-VLAN Routing enabled.
- DHCP server configured for each subnet.
- Subinterfaces created for each VLAN to ensure seamless communication.
Switch Configuration
- VLANs created and assigned to appropriate ports.
- Trunk port configured for router connection.
Wireless Networks
Each department is equipped with a dedicated wireless access point, ensuring secure and separate wireless connectivity.

## 🔒 Security Measures
VLAN Segmentation: Isolating department traffic to enhance security.
DHCP Snooping: Protects against rogue DHCP servers.
Port Security: Secures access ports to prevent unauthorized devices from connecting.

## 📊 Network Diagram
<details> <summary>Click to view screenshots</summary>
System Design
   
![10](https://github.com/user-attachments/assets/101dddff-4a2b-48b0-97a4-bfad22a80465)

VLAN Configuration on Switch

![2](https://github.com/user-attachments/assets/2a8cc8ea-15cf-4d20-b85c-9b5bd1ce74bf)


Router Subinterface Setup

![7](https://github.com/user-attachments/assets/06220833-fb1d-43fd-a71e-5131d61c9882)


DHCP Configuration

![13dhcp configration](https://github.com/user-attachments/assets/705ecc84-0306-4f0f-af5d-bacb8d7274dc)

Inter-VLAN Communication Test

![6](https://github.com/user-attachments/assets/9cbb5914-1381-4bc1-9be0-2774cab0bfd5)


Wireless Network Setup

![5](https://github.com/user-attachments/assets/2653c0ff-2180-4a36-983e-c38a15b18192)

</details>
🤝 Contributing
Contributions are what make open-source projects amazing. Any contributions you make to enhance this project are greatly appreciated.

Fork the project repository.
Create your feature branch (git checkout -b feature/AmazingFeature).
Commit your changes (git commit -m 'Add some AmazingFeature').
Push to the branch (git push origin feature/AmazingFeature).
Open a pull request.
📄 License
Distributed under the MIT License. See LICENSE for more information.

📞 Contact
Mumtaz Ali - engrmumtazali01@gmail.com

Project Link: https://github.com/engrmumtazali0112/networking_smtr_project

<p align="center"> <a href="mailto:engrmumtazali01@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a> <a href="https://www.linkedin.com/in/mumtaz-ali"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a> <a href="https://github.com/engrmumtazali0112"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"/></a> </p>
<p align="center">This project is developed as part of our semester project with ❤️ by Mumtaz Ali</p>
