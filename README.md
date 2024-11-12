# ECS-Exec

<img src="images/how-to-use.gif" width="1000" height="500"/>


## Requirements
- [AWS CLI](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html)
- [session-manager-plugin]( https://docs.aws.amazon.com/systems-manager/latest/userguide/session-manager-working-with-install-plugin.html)
- [jq](https://stedolan.github.io/jq/download/)

## QuickStart

1. Clone the repository
```bash
git clone https://github.com/iYasha/ecs-exec.git
```
2. Change directory to the cloned repository
```bash
cd ecs-exec
```
3. Make the script executable
```bash
chmod u+x ecs-exec
```
4. Run the script
```bash
./ecs-exec
```

## Add script to PATH
To add the script to the PATH, run the following command:

For bash:
```bash
echo 'export PATH="$PATH:'"$(pwd)"'"' >> ~/.bashrc && source ~/.bashrc
```
For zsh:
```bash
echo 'export PATH="$PATH:'"$(pwd)"'"' >> ~/.zshrc && source ~/.zshrc
```