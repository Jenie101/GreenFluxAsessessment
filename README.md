# GreenFluxAsessessment

DevSecOps Assignment

You are only DevOps engineer in Solar Impulse. You receive request to deploy following
infrastructure.
One vNet named solar-impulse-test with subnet that contains one Azure Container Instance. Docker
image should be based on official dnsmasq docker image with configuration:
server=8.8.8.8
server=8.8.4.4
Second vNet solar-impulse-acc with subnet that contains one VM. VM should be accessible from
195.169.110.175 with password authentication type. Solar-impulse-test and solar-impulse-acc need
to be connected. NSG on subnet level is only protection required.
Your task is:

To provide deployment scripts (PowerShell or Azure CLI).
To describe CI/CD pipelines for your scripts.
To point out your security concerns and advise about security improvements for the deployed
infrastructure.
Challenges experienced.
