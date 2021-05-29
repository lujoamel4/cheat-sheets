# system's file watchers limit

If you are using Linux, your project is hitting your system's file watchers limit

To fix this, on your terminal, try:

echo fs.inotify.max_user_watches=524288 | sudo tee -a /etc/sysctl.conf && sudo sysctl -p

https://stackoverflow.com/questions/53930305/nodemon-error-system-limit-for-number-of-file-watchers-reached
