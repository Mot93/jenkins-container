# jenkins-container-iac
Using Jenkins requires that each agent has installed the necessary tools.

To bypass this problem, it's possible to execute each pipeline in a container tailor made for it.
Therefore achieving iac by defining the infrastructure in a Dockerfile.

This repo is an example of how to achieve this goal with a python script.