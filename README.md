Create ansible automation that:
- Checks if TLS certificate exists.
- If certificate does not exist or is expired creates new one that will expire in 30 days.

Below given recommendations are not a must but will make accomplishing the task easier.

Recommendations:
- Use linux machine.
- If you do not have it already install ansible in virtual environment with following commands:
```
python3 -m venv ~/ansible-venv
~/ansible-venv/bin/pip install ansible
```
to use short comands without refering to binaries in virtual environment execute:
```
echo 'PATH="$HOME/ansible-venv/bin:$PATH"' >> ~/.profile
. ~/.profile
```
- I suggest using repo structure provided here, otherwise please provide necesary configuration.
- use virtual fortigate with evaluation license hosted on VMware Workstation Player/Pro.

Important:
- Please document what and why is being done.
- Try to create reusable, modular code.
- DO NOT PUSH ANY SECRETS TO GIT.

If you are configuring any kind of password with ansible use ansible-vault and share vault password in email when turing in the task.

For submission, please clone this repo and add the files to your own, PRIVATE repository. Invite me(owner of this repo) as a reviewer. Create a new branch, do your solution and create PR to the main, do not merge.
