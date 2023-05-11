# read-log-file
- In readlog.Rmd, we read different sessions from the .log file, using regex to match the pattern
- The data is shown with the column name:"date-time", "logging host", "app", "PID", "message", "log file"
- Then we analyze it by data-time, app, and especially message, to get some insights of the log file such as the statistical information about the related ip address.
