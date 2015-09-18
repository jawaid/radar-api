# radar-api

API for simple node application to view issues on github. Communicates with github API. By default, runs on port 3001.

[![Build Status](https://api.shippable.com/projects/55f0a3801895ca447414401d/badge?branchName=master)](https://img.shields.io/shippable/55f0a3801895ca447414401d.svg)
[![Build Status](https://api.shippable.com/projects/55f0a3801895ca447414401d/badge?branchName=master)](https://app.shippable.com/projects/55f0a3801895ca447414401d/builds/latest)
[![Build Status](https://api.shippable.com/projects/550a83015ab6cc1352a4c97c/badge?branchName=master)](https://app.shippable.com/projects/550a83015ab6cc1352a4c97c/builds/latest) 
# New Badge
[![Build Status](https://api.shippable.com/projects/55f0a3801895ca447414401d/badge?branchName=master)](https://app.shippable.com/projects/55f0a3801895ca447414401d/builds/latest) 
# https://app.shippable.com/projects/55f0a3801895ca447414401d
# Environmental variables

- API_PORT: To run on a specified port (default: 3001). Make sure that the front end is gets the change accordingly
- NODE_ENV: Either 'dev' or 'test', modifies status page
- CONSOLE_LOGLEVEL: Specifies log level for winston console (silly, debug, verbose, info, warn, error). The app only uses info and error messages.
- FILE_LOG: true or false, specifies whether to save logs to logs.log
