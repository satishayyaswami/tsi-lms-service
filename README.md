## TSI GRC Service

TSI GRC Service, a part of TSI Digital Accelerator, exposes core backend services of a IT Governance, Risk & Compliance Solution as REST APIs.

### Getting Started

#### Init setup

- Install <a href="https://www.postgresql.org/download/">PostgreSQL</a> database
- Clone TSI GRC Service into your Projects folder
- Create the _tsi_grc_service database and the demo user by following the instructions in db/setup.sql. Make sure that the same database credential is configured in web/WEB-INF/_config.tsi 
- Install <a href="https://openjdk.org/projects/jdk/17/">Open JDK</a> and <a href="https://ant.apache.org/bindownload.cgi">Apache Ant</a>
- Edit the tsi-grc-service.bat and change the installation directories as appropriate
- Start the TSI GRC Service by running the tsi-grc-service.bat in a cmd window

