# sap-s4hana-2022-on-docker
SAP S/4HANA 2022 SP01 on Premise using Docker

System specification:

OS Linux Ubuntu 22.04 LTS, Docker CE (Community Edition) version 26.1.1, build 4cf5afa, SAP GUI for Java 7.80 rev 3, Eclipse IDE for Enterprise Java and Web 

Developers 2024-12

Hardware specification:

PC desktop LGA 1151, Intel i7 8700, SSD M2.SATA 1 TB, RAM 32 GB DDR4, VGA card 2 GB

![alt text](https://github.com/jenizar/sap-s4hana-2022-on-docker/blob/main/screenshot/pic1.png)

Check status docker:

$>systemctl status docker

Start docker:

$>sudo docker start -ai a4h

Stop docker:

^C (Ctrl + c) // $>sudo docker stop -t 7200 a4h

![alt text](https://github.com/jenizar/sap-s4hana-2022-on-docker/blob/main/screenshot/pic2.png)

![alt text](https://github.com/jenizar/sap-s4hana-2022-on-docker/blob/main/screenshot/pic2a.png)

conn=/H/localhost/S/3200

![alt text](https://github.com/jenizar/sap-s4hana-2022-on-docker/blob/main/screenshot/pic3.png)

username: DEVELOPER

password: ABAPtr2022#01

![alt text](https://github.com/jenizar/sap-s4hana-2022-on-docker/blob/main/screenshot/pic4.png)

System Status

![alt text](https://github.com/jenizar/sap-s4hana-2022-on-docker/blob/main/screenshot/pic5.png)

License

![alt text](https://github.com/jenizar/sap-s4hana-2022-on-docker/blob/main/screenshot/pic6.png)

List Program ABAP

![alt text](https://github.com/jenizar/sap-s4hana-2022-on-docker/blob/main/screenshot/pic7.png)

Output program ABAP

![alt text](https://github.com/jenizar/sap-s4hana-2022-on-docker/blob/main/screenshot/pic8.png)

Eclipse IDE for Enterprise Java and Web Developers 2024-12

References:

1. https://community.sap.com/t5/technology-blogs-by-sap/abap-cloud-developer-trial-2022-available-now/ba-p/13598069

2. https://hub.docker.com/r/sapse/abap-cloud-developer-trial

3. https://github.com/SAP-docs/abap-platform-trial-image/blob/main/faq-v7.md

4. https://www.youtube.com/watch?v=98Sc3356O9k

5. https://developers.sap.com/trials-downloads.html
