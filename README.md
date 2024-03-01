# Kanata-Service
A macOS launchctl wrapper to run Kanata(keyboard remapper) on startup/load as a daemon.

## Manual
```sh
$ kanata-service help
```
```
Usage:
    Installation: kanata-service install <kanata_binary> <kanata_config>
    Other: kanata-service <command>
Available commands:
    1. install - installs the launchd com.kanata.plist file & and adds kanata to sudoers.d
    2. uninstall - deletes the launchd com.kanata.plist file & removes the kanata sudoers.d
    3. start - starts the service
    4. stop - stops the service
    5. restart - restarts the service
    6. info - prints properties of the com.kanata launchd service
    7. debug - concatenates the stderr.log to stdout"
```
