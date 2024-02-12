internsctl is a command-line tool designed for system information retrieval and user management tasks. It provides functionalities to fetch CPU information, memory details, manage users, and retrieve file information.

Features
Fetch CPU information using cpu getinfo.
Retrieve memory details using memory getinfo.
Create a new user with user create <username>.
List all users or only sudo users with user list [--sudo-only].
Retrieve file information including size, permissions, owner, and last modified time.
Installation
Simply download or clone this repository to your local machine:

git clone https://github.com/neerajsharma684/internsctl.git


## Ensure the script (internsctl.sh) has executable permissions:
- chmod +x internsctl

Usage
Run the tool using the following syntax:

./internsctl [options] <command>
Examples

1. Fetch CPU information:
        ./internsctl cpu getinfo
       
2. Create a new user:
        ./internsctl user create <username>

3. Retrieve memory information:
        ./internsctl memory getinfo
       

4. List all the available options:
        ./internsctl ls

        
4. For more details and available commands, refer to the help message:
        ./internsctl --help
       
