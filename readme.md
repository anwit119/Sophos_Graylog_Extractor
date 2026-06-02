# Sophos SFOS Syslog Graylog Extractor

This repository contains a custom modified JSON Graylog extractor for Sophos SFOS Syslog.

Forked by me from https://github.com/rahoulrdhopade/Sophos_Graylog_Extractor for some minor changes for my own enviroment

## Tested Environment

The extractor has been tested and confirmed to work with logs available in the following environment:
- Graylog Version: 6.x
- Sophos SFOS 22.x on Sophos XGS 2300

### Change befor import:
You have to Update the Device Name to your enviroment:
      "condition_value": "device_name=\"insert.device.name.here\""
