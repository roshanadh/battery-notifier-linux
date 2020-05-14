# battery-notifier-linux
Scheduled notifications in your Linux system regarding battery status and charge

## Usage
* Clone the repository
    ```sh
    git clone https://github.com/roshanadh/battery-notifier-linux
    ```
* Install dependencies from inside the clone
    ```sh
    cd battery-notifier-linux && npm install
    ```
* Run the script
    ```sh
    node index.js
    ```

## Run the script on system startup
* Install pm2 globally
    ```sh
    npm install -g pm2
    ```
* Start index.js from inside the clone
    ```sh
    pm2 start index.js
    ```
* Create a startup script
    ```sh
    pm2 startup
    ```
    Copy and Paste the output of the above command in the terminal

* Save the list of processes to spawn on system startup
    ```sh
    pm2 save
    ```