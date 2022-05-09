# Lab Report 3

- **Streamlining ssh Configuration**
    
    To log onto the remote server, I typically have to type the `ssh` command alongside all my login information such as my username and password. In this part of the lab, I altered a config file to include the remote server's hostname and my own username to speed up the login process.

    
    This is the config folder that I edited on VScode with the connection information.

    ![config](config.PNG)

    Below is a successful ssh login with the configuration.

    ![config_login](config_login.PNG)

    This is the file listing of a successful copy using scp.

    ![scp_copy](scp_copy.PNG)
---
- **Setup Github Access from ieng6**

    In this part of the lab, I generated a new ssh key on the remote server and copied the contents of the public key to my Github account.

    ![pub_key](pub_key.PNG)

    The private key is held in the .ssh directory of the remote server.

    ![private_key](private_key.PNG)

    These are some git commands that are being used on the remote server.

    ![git_command](git_commands.PNG)
    This is the link for the commit.
    [https://github.com/clarksonphan/skill-demo/commit/e7cec30c31c51c1fe86b6a7ef453a4f92820911c](https://github.com/clarksonphan/skill-demo/commit/e7cec30c31c51c1fe86b6a7ef453a4f92820911c)

---
- **Copy whole directories with `scp -r`**

    With the `scp -r` command we are able to copy whole directories with one command rather than using the scp command to copy singular files. 

    ![scp_directory](scp_directory.PNG)

    This is my test running successful from the remote repository.

    ![scp_directory_test](scp_directory_test.PNG)

    In this line, several commands are combined in order to copy and run the tests.

    ![one_line](one_line.PNG)