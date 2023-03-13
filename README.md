# my5G-RANTester-Script
Script to run my5G-RANTester

## How to run
1. Install Linux Kernel **v5.4.90** following [this tutorial](https://www.how2shout.com/linux/how-to-change-default-kernel-in-ubuntu-22-04-20-04-lts/).

2. Install `curl`:

    ```bash
    sudo apt update
    ```
    
    ```bash
    sudo apt -y install curl
    ```

3. Run the script for open5gs:
    - Open5GS:

      ```bash
      sudo -s
      ```

      ```bash
      bash <(curl -s https://raw.githubusercontent.com/lucas-schierholt/my5GRANTester-Script/main/run.sh) -c 2
      ```

      

      
      
      