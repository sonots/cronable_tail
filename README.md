# cronable_tail

crontable_tail enables to read log files in tail even if the log files are logrotated such as

    /var/log/syslog.20130130
    /var/log/syslog.20130131

cronable_tail memorizes the line number which previously read, and continues to read from
the line in the next execution. Of course, if a newer file is generated, it reads the newer file too.

# Copyright

- Copyright (c) 2013- SEO Naotoshi (sonots)
- License: MIT License

