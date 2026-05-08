# ozmofilters
These are a set of filters for uBlock Origin that blocks pleas, ads not blocked with default filters, and annoyances. The subscription pleas filter does not block paywalls.

## Note
This has been migrated to the Codeberg repository [ozmoozmo/ozmofilters](https://codeberg.org/ozmoozmo/ozmofilters).

## Installation
[Open](https://github.com/gorhill/uBlock/wiki/Dashboard) the uBlock Origin dashboard, go to the "Filter lists" tab and paste the following into the Import tab:
```
https://codeberg.org/ozmoozmo/ozmofilters/raw/branch/main/advertisements.txt
https://codeberg.org/ozmoozmo/ozmofilters/raw/branch/main/annoyances.txt
https://codeberg.org/ozmoozmo/ozmofilters/raw/branch/main/donation-pleas.txt
https://codeberg.org/ozmoozmo/ozmofilters/raw/branch/main/subscription-pleas.txt
https://codeberg.org/ozmoozmo/ozmofilters/raw/branch/main/login-pleas.txt
https://codeberg.org/ozmoozmo/ozmofilters/raw/branch/main/notification-pleas.txt
```

## Migration
Delete your current imported ozmofilters, and import the filters as described in the installation instructions above.
