# chef-aps-inspec-mysql Inspec Profile
[![Build Status](https://travis-ci.org/Alfresco/chef-aps-inspec-postgres.svg)](https://travis-ci.org/Alfresco/chef-aps-inspec-postgres?branch=master)

Inspec profile for [chef-aps-db](https://github.com/Alfresco/chef-aps-db) cookbook

To use it in your Kitchen suite add:

```
verifier:
  inspec_tests:
    - name: chef-aps-inspec-mysql
      git: https://github.com/Alfresco/chef-aps-inspec-postgres
```
