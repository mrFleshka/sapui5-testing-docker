# Info

SAPUI5 Testing practice (For SAPUI5 version: 1.65.1).

[Documentation](https://sapui5.hana.ondemand.com/#/topic/291c9121e6044ab381e0b51716f97f52)

Used with docker (nginx proxy-pass + node server).
 
# Run

For start add network in docker (used for custom windows network with routing to virtual machine):

```bash
docker network add develope
```

Then just start docker:

```bash
docker-compose up
```

Demo site available at [testing.sapui5.test](http://testing.sapui5.test/test.html)