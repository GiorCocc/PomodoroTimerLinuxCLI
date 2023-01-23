# PomodoroTimerLinuxCLI

Pomodoro timer for linux commandline with graphical timer, sound, voice and notification built-in

## Installation

Copy the instructions under `pomodoro.sh` inside the `.bashrc` of your linux home directory `/home/<username>/.bashrc`

To be able to use the pomodoro timer you need to install:

- timer (from [caarlos0/timer](https://github.com/caarlos0/timer))
- lolcat `sudo dnf install lolcat`

To change the default work-time and break-time, modify the followed line of the script

```bash
pomo_options["work"]="<your default work time>"
pomo_options["break"]="<your default break time>"
```

## Commands

Start pomodoro and set loops: `doro <number of rounds>` (If you type doro without specifying a number, it will perform the default number of loops that are set in the script.).

Change work time: `cp work <time in minutes>`

Change break time: `cp break <time in minutes>`
