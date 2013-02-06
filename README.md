# cronable_tail

crontable_tail is a shell script to read log files in tail. It memorizes the line number which previously loaded, and continues reading from the next line on the next execution.

Furthermore, this script supports reading logrotated log files such as

    /var/log/syslog.20130130
    /var/log/syslog.20130131

This script reads the newly generated file too if such a file exists.

# Copyright

- Copyright (c) 2013- SEO Naotoshi (sonots)
- License: MIT License

