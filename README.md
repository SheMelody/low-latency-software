# Melody's Low Latency Software

![v3](https://github.com/SheMelody/low-latency-software/assets/20774468/a20cf821-6ad6-4b2e-b1d9-3f647c988139)

[Official Download Page](https://sites.google.com/view/melodystweaks/lowlatencysw)

# If you get "100% CPU usage" after enabling Low Latency, that's a visual bug indicating that idle cycles have been disabled to provide the lowest latency. Please don't ask the reason of "100% CPU usage"!

- What this program does is setting a temporary power plan and set the timer resolution to the lowest value supported.


Designed for Windows 10 1803 and newer, Windows 11 and newer.

Only for 64-bit systems.


- This program requires the Power Service to be running. The program might ask the user to enable it.

- It is not adviced to run this program in stripped / modified systems. Do it at your own risk.

- For debug information hold SHIFT, CTRL or ALT in the main window.

- Use the mouse icon in my program to set queue sizes and platform tick.

- When using my program, it is adviced to use platform tick because of the way it works.

- It is not adviced to run the program on unsupported Windows versions and I don't plan to support them anytime soon in this program.


Command-line Parameters (V3.0 and newer)

You can supply 3 parameters on startup:

\[mode\] \[minimize\] \[steer\]

- mode can be 1, 2, 3 and it specifies Low Latency Mode status on startup, 1 = only enable Timer Resolution, 2 = enable Low Latency Mode without Timer Resolution, 3 = Enable Low Latency Mode.

- minimize can be set to minimize to minimize the program on startup.

- steer can be set to steer to enable interrupt steering.

You can set any parameter to an empty string ("") or just supply an invalid value to make the program ignore it.

Example: MelodysLowLatencyUI_v3.exe 3 nominimize nosteer


When having problems, please post a full screen of the debug screen.

Join our Discord here: http://discord.gg/6TMHU63
