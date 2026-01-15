# RunAnsibleViaGithubActions
Call the ansible playbook and give it different values coming from the user

# The Plan

Have a file that has the user entered values.
Have a github action that will run manually by the user.
Have a Ansible play book.
Ansible playbook will require environment variables.
Github action will run the ansible playbook job.
When running it will input the user file as environment variables.

Just make an easy ansible job, this will run on the local machine.
It will take in an environment variable and it will print it.

# Run Environment

ansible-env\Scripts\activate

