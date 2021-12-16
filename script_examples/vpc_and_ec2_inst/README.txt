First, make sure you have your static website in a zip format. Then select the zip file and make it public for an Access Control List (ACL). 
Copy the URL to access this zip file and embedded in the UserData script. Add the command wget with your zip file URL and another command to unzip the file. 
These commands should be after the metadata is created. The metadata section contains instructions to install the package httpd, an Apache for our instance.

This script is available in my Github repository at https://github.com/raulFuzita/cct-cloud-services/tree/cloudformation/script_examples/vpc_and_ec2_inst.

I also created an application in Jupyter Notebook on Google Colab that generates the template without a single line of code. If you want to use my application, please click on this link and read the instruction carefully:
https://colab.research.google.com/github/raulFuzita/cct-cloud-services/blob/cloudformation/script_examples/vpc_and_ec2_inst/cloudformation_vpc_and_ec2_instance.ipynb
