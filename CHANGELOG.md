# Version 0.1.9

## Features
- Look for headers instead of header in request: `headers` used in REST, header used in Postman JSON


# Version 0.1.8

## Features
- Split up functions into data modules 
- Split up tests for each module
## Deprecations and Removals
- Removed the ability to add example. Since Postman doesn't allow for Example requests to be sent, there is no point at the moment. 

##  Bugfixes
- allow examples with no query parameters

# Version 0.1.7

## Features
- Use INI divider to parse doc strings 
- Use body, and header keys inside INI to pass header, body values. 
- Added abiliity to add examples from doc strings using [examples.xxx] section 

# Version 0.1.6

## Features

- CHANGELOG
- format_json_body, which parses doc strings for JSON BODY examples requests. The function adds the JSON as Body request code in Postman. 

##  Bugfixes
- 

## Deprecations and Removals

     warning
> None to mention