## Overview

This setup uses Docker Compose to orchestrate three main services:

- **app**: PHP-FPM container for Laravel backend
- **node**: Node.js container with Angular CLI for frontend development
- **mysql**: MySQL database container

All containers share a custom bridge network and persistent volumes for code and database data.