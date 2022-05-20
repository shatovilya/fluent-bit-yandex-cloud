# fluent-bit-yandex-cloud
The project runs Fluent Bit with the included Fluent Bit application for Yandex Cloud Logging.

---

## Pre-deployment preparation

---

Before deploying the project, install Docker, Docker Compose latest versions.

---

## Installation

---

For installation:
To install, run:

1. Do a git clone.

2. Create an .env file and fill with variables:

```bash
cp ./.env_temp ./.env

```

3. Add iam-key-file 

Generate it via the Yandex Cloud command line interface.

Аdd it to the project root.


4. Run the project

```bash
docker-compose up -d

```

5. After a couple of minutes, the service will start.

---


### Useful links

---

[Fluent Bit plugin for Yandex Cloud Logging](https://github.com/yandex-cloud/fluent-bit-plugin-yandex)
