## Usage

Usage instructions for the `install-afc.sh` script can be shown at any time by running the following command:

```bash
./install-afc.sh -h
```

An example output is shown below:

```bash
Usage: install-afc.sh [options]

Options:
  -a <moonraker address>      Specify the address of the Moonraker server (default: http://localhost)
  -k <path>                   Specify the path to the Klipper directory
  -m <moonraker config path>  Specify the path to the Moonraker config file (default: ~/printer_data/config/moonraker.conf)
  -n <moonraker port>         Specify the port of the Moonraker server (default: 7125)
  -s <klipper service name>   Specify the name of the Klipper service (default: klipper)
  -p <printer config dir>     Specify the path to the printer config directory (default: ~/printer_data/config)
  -b <branch>                 Specify the branch to use (default: main)
  -y <klipper venv dir>       Specify the klipper python venv dir (default: ~/klippy-env/bin)
  -h                          Display this help message

Example:
 ./install-afc.sh [-a <moonraker address>] [-k <klipper_path>] [-s <klipper_service_name>] [-m <moonraker_config_path>] [-n <moonraker_port>] [-p <printer_config_dir>] [-b <branch>] [-y <klipper venv dir>] [-h]
```


## Command Line Options