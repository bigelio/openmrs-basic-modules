# openmrs-basic-modules

<strong>Note:</strong> This was tested on macos

### 1.  Make sure [openmrs-core](https://github.com/openmrs/openmrs-core) is installed and configured with mysql database.

### 2. After cloning this repo, run this command to copy the modules to your **openmrs** modules directory

```bash
cd openmrs-basic-modules && cp ./*  .OpenMRS/modules/
```

### 3. The legacy module for user interface is included. If you want to build it on your own checkout the repo [here](https://github.com/openmrs/openmrs-module-legacyui) 
### 4. Start the server after making sure that the **mvn** is configured or run it with **docker** . In **openmrs-core** directory 
 ```bash
cd webapp && mvn jetty:run
```
### 5. Now the app should be accessible in the browser at the port displayed in terminal.



