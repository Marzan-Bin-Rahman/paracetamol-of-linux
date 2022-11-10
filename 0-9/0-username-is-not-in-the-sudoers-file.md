# **Problem - 0 : ** I am unable to be root user in debian after fresh installation. It shows 'My username is not in the sudoers file'.

- Open your terminal.
- Type
     ```sh
     su
     ```
     Then enter your password and your root. But our work is done yet.
     ![Be root by typing `su`](../assets/0-username-is-not-the-sudoers-fie/beeing-root.png "Be root by typing su")
- Then type
     ```sh
     nano /etc/sudoers
     ```
     ![Finding the file](../assets/0-username-is-not-the-sudoers-fie/finding-the-file.png "Finding the file")