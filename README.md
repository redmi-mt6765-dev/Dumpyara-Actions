# Dumpyara-Actions
Generate a dump from an archive or image(s) via GitHub Actions.

# dumpyara

**Script requirements**:

      Linux or Mac
      
***For setting up requirements***:

      bash setup.sh

**Usage**:

      bash dumpyara.sh "<OTAlink> OR <OTA file path>" yourGithubToken

You can also place your github oauth token in a file called `.githubtoken` and telegram bot token in a file called `.tgtoken` in the root of this repository, if you wish it is ignored by git.  
Before you start, make sure that dumpyara scripts are mapped to your own org or account, otherwise you'll only dump, not push.  

**Supported image types**:  
check [here](https://github.com/redmi-mt6765-dev/Firmware_extractor/blob/master/extractor.sh#L3)  
