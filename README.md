> ### Deprecation Notice: See https://github.com/WisdomSky/windows-palworld-server-docker instead.

---

# Palworld Windows (WIN64) Dedicated Server Docker

Run Palworld Windows server on Docker (Linux) via Proton


Installation:

1.) Copy and setup the `.env` file.
```
cp .env.default .env
```

*(Optional)* Update the environment variables.
2.) 
```
vi .env
```

3.) Build and start the server
```
sudo docker compose up -d
```

---

This setup was isolated from https://github.com/Dekita/palhub-server
