# enable_fips_role
This enables FIPS mode on CentOS 7

This role was intended for our environment where we have several servers, including ElasticSearch, where we want to enable fips inside production (Or a newly spun up server). 

If it does enable on a production server, and it has to reboot said ES server, it then waits to make sure the cluster is green. 

I have not provided the environmental folders/variable_files for this role as of right now. 
#TODO add var files and main.yml for environment examples.
