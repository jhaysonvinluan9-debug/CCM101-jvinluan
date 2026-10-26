Multi-Tier Architecture

What is a Two-Tier Architecture?

A two-tier architecture is a system that separates an application into two main parts: the web/application tier and the database tier. 
These tiers communicate with each other to provide services to users. In this laboratory, Nextcloud serves as the application, while MariaDB stores the application’s data.

The Web/Application Tier

The web/application tier handles user requests and provides the web interface. In this project, Nextcloud runs inside a Docker container 
and allows users to access the private cloud storage system through a web browser. It communicates with the database to retrieve and save information.

The Database Tier

The database tier stores and manages persistent application data, such as user accounts, settings, and file metadata. In this project, 
MariaDB runs in a separate Docker container and provides database services to Nextcloud.

Why Separate Them?

Separating the web application and database into two containers makes the system easier to manage and
