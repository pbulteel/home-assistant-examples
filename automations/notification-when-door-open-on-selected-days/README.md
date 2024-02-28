# Notify when door is open on selected days

In this automation, you will get a notification when binary_sensors for the days of the week have been enabled. It works when both the day of the week is also the day the binary_sensor is enabled for. By that I mean, if the day of the week is Monday AND the Monday option is selected, then the automation will run.

You will need to create binary_input helpers for each day of the week. And you need to select one of the two notification methods. In the first instance you need to select you device and in the second one, it uses the notify.mobile_app_your_device so you need to select what your device is for that one.
