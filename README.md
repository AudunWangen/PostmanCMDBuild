# Prerequisites

Postman 8 or a client to read Postman files in version 2.1-format.

# Usage

Import the file into Postman and change the parameters according to your needs.

All variables need to be set up manually as environment variables (see below)

## Environment variables

Go under Environments and set up a new environment. This should contain the base url for CMDBuild and a username and password with API permissions. You don't have to set sessionid, because that should be automatically set when you run "Generate session token".

| Variable      | Example                                                   | Explanation             |
|---------------|-----------------------------------------------------------|-------------------------|
| cmdbuild_url  | https://cmdbuild.katalog.intern/cmdbuild/services/rest/v3 | The url to the REST API |
| username      | admin                                                     | Username                |
| password      | admin                                                     | Password                |
| sessionid     | d42v4vdemzezfqdkjivdzo0h                                  | Session ID or token     |

The available queries are just a subset, so see [the webservice manual](https://www.cmdbuild.org/file/manuali/webservice-manual-in-english) for a more detailed descriptions of availble endpoints, functions, paths and parameters.