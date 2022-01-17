## Description

**GoogD0rker** is a tool for firing off google dorks against a target domain, it is purely for OSINT against a specific target domain. This will output all the google results for each of the tasks so you can hopefully find a vunerability. A 503 error means you need a new IP as google knows you're up to something! This will output the results to files and then you can browse and see what you have found.

## Usage

The usage command, for example:
```
docker run -it --rm secsi/googd0rker -d <target_domain>
```