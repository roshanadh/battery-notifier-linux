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
* Make the script executable
    ```sh
    chmod 555 run-script.sh
    ```
* Execute the script
    ```sh
    ./run-script.sh
    ```

## Run the script on system startup
* Open up 'Startup Applications' program from System > Preferences
  
* Locate and add 'run-script.sh' as a startup application
