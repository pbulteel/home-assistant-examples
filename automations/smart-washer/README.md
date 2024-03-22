# Make your dumb washer smart

What do you do if you have a dumb washer or dryer? One that doesn't have Wifi and therefore cannot be integrated into Home Assistant? Well, you make it smart with different components.

However, you don't NEED to start with components to make it smart, you can fake it by creating the automations and scripts and simply using your "manual" process to trigger the automations. Once you buy the different components to help make it smart, you can simply swap those for the manual process.

It's all about getting to the logic. I'll break it down here and then provide the scripts and automations that use the manual process. Once I have that, I'll then substitute them with the one that fully automates the task.

1. Button to trigger the automation that the wash is started.
2. Timer or workflow which waits for the washer to be done.
3. Button to trigger that the wash has been removed from the washer.

Each automation can be found in the respective yaml.
