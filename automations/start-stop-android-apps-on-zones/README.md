# Start and Stop android apps on your Android phone

Using the Home Assistant Companion app on Android (and iPhone) you can start applications. With Android you can also have some apps perform activities using Intents. The example in this automation is using the WiGLE wifi scanning app.

I have throught to turn part of this as a script that I call from this automation. Meanwhile, enjoy!

## What does this automation do?

It triggers based on entering or leaving zones (Home, stores (Co-op, Tesco, Sainsbury's), my rail station, Costa) and avoids running if the battery level is 10%. You have to setup all those zones. They can be set to "passive".
