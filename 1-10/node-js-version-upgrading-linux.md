# **Problem - 1 :** How to update my Node.js version in linux / Debian / Ubuntu / Kali?  

#### There is a common problem seen by the linux users that when they install Node.js, the version of Node.js is pretty much older. And now, you want to update it to the latest version or the stable version or to any other version of Node.js. You will find many solution across the web. But I will show you one of the most easiest ways of solving the problem.

## Prequisites
 - Should have npm installed

    Install npm in Debian / Ubuntu / or ZorinOS
     ```sh
    sudo apt install npm
     ```
     Install npm in Fedora and in it's derivatives
     ```sh
    sudo dnf install npm
     ```

### Now you are ready to update your Node.js version
1. ```sh
    npm cache clean -f
    ```
    ![npm](../assets/node-js-version-update/npm-cache-cleaning.png)
2. ```sh
    sudo npm install -g n
    ```
    ![npm](../assets/node-js-version-update/install-node-version-manager.png)
3. Now you have three choice. Either install the latest version or the stable version or any other version you want.
      1. Install the **Stable** version
         ```sh
         sudo n stable
         ```
         ![npm](../assets/node-js-version-update/stable-version-installing.png)
    2. Install the **Latest** version
        ```sh
        sudo n latest
        ```
        ![npm](../assets/node-js-version-update/installing-latest-version.png)
    3. Install a version of you choice
        ```sh
        sudo n [version.number]
        ```
        for example
        ```sh
        sudo n 19.0.0
        ```
        ![npm](../assets/node-js-version-update/installing-any-version.png)