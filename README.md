<h1>Cron Wrapper</h1>

This dirty tool can execute code more frequently than 1 minute which is crontab minimum setting

<h2>Warning</h2>

executing stuff too frequently can be harmfull for the system. This wrapper does not verifies if the previous execution is finished or not.

<b>ENSURE THAT THE CODE IS FINISHING QUICKLY</b>

<h2>Usage</h2>

Add to cron, where X is the delay between executions in seconds

*/1 * * * * /root/bin/wrapper X

For exemple : every 10 seconds

*/1 * * * * /root/bin/wrapper 10









