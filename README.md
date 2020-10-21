# test_anna
Key  | Type | Required  | Description | Default
------------- | ------------- | ------------- | ------------- | -------------
mcf_version  | string  | false  | version of MCF to use.  | 1.0 
name  | string  | true  | Name of the project. If you want to reference this in later configuration, it must meet the minimum requirements of the target platform(s) being deployed to. For example, Google App Engine requires that many IDs/names must be 1-63 characters long, and comply with RFC1035. Specifically, the name must be 1-63 characters long and match the regular expression [a-z]([-a-z0-9]*[a-z0-9])?. The first character must be a lowercase letter, and all following characters (except for the last character) must be a dash, lowercase letter, or digit. The last character must be a lowercase letter or digit.  | none
version | string | false | deployment version of your application/service. Version must contain only lowercase letters, numbers, dashes (-), underscores (_), and dots (.). Spaces are not allowed, and dashes, underscores and dots cannot be consecutive (e.g. "1..2" or "1._2") and cannot be at the beginning or end (e.g. "-1.2" or "1.2_") | ------------- 
labels  | string  | false  | a collection of keys and values to represent labels required for your deployment.  | none   


