#### IntelliJ inspection gives “Cannot resolve symbol” but still compiles code
First of all you should try File > Invalidate Caches, else https://intellij-support.jetbrains.com/hc/en-us/articles/206544519-Directories-used-by-the-IDE-to-store-settings-caches-plugins-and-logs

### Setup WildFly configuration file (eg: standalone-full-xml)
In the Run/Debug configuration for your server in the tab Startup/Connection you have the ability to set Startup script: On the end of line there is checkbox Use default. Please unselect it and paste on the end of the input -c standalone-full.xml
- https://stackoverflow.com/questions/25849810/how-to-run-wildfly-with-standalone-full-xml-from-intellij-idea
