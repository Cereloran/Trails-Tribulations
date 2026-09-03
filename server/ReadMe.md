# Versions
Minecraft 26.1.2
Neoforge 26.1.2.78

# You need these ports open by default
Server Dafault Port: 25565
Voicemod Port: 24454

Minimum 8gb of ram should suffice; initial world gen is kinda pricey in this pack. 12gb of RAM Maximum.
If you don't want your server succumbing to tick death; use the configs provided as a baseline <3

My JVM args:

# JVM args for the NeoForge server launcher.
# Keep this file small and predictable; the launcher reads it directly.

-Xms8G
-Xmx10G
-XX:+UseG1GC
-XX:+ParallelRefProcEnabled
-XX:MaxGCPauseMillis=200
-XX:+UnlockExperimentalVMOptions
-XX:+DisableExplicitGC
-XX:+AlwaysPreTouch
-XX:G1NewSizePercent=30
-XX:G1MaxNewSizePercent=40
-XX:G1HeapRegionSize=8M
-XX:G1ReservePercent=20
-XX:G1HeapWastePercent=5
-XX:G1MixedGCCountTarget=4
-XX:InitiatingHeapOccupancyPercent=15
-XX:G1MixedGCLiveThresholdPercent=90
-XX:G1RSetUpdatingPauseTimePercent=5
-XX:SurvivorRatio=32
-XX:+PerfDisableSharedMem
-XX:MaxTenuringThreshold=1
-Dfile.encoding=UTF-8
-Dusing.aikars.flags=https://mcflags.emc.gs
-Daikars.new.flags=true

