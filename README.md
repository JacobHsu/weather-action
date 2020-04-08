# weather-action

GitHub Actions 教程：[定时发送天气邮件](http://www.ruanyifeng.com/blog/2019/12/github_actions.html)  

Time Zone in Taiwan [Asia/Taipei](https://www.zeitverschiebung.net/en/timezone/asia--taipei)

weather-action/Secrets `gmail` MAIL_PASSWORD, MAIL_USERNAME

cron-job-schedules [Defining the Job Schedule](https://cloud.google.com/scheduler/docs/configuring/cron-job-schedules?hl=zh-tw)


[Scheduled events](https://help.github.com/en/actions/reference/events-that-trigger-workflows#scheduled-events-schedule): schedule

```js
┌───────────── minute (0 - 59)
│ ┌───────────── hour (0 - 23)
│ │ ┌───────────── day of the month (1 - 31)
│ │ │ ┌───────────── month (1 - 12 or JAN-DEC)
│ │ │ │ ┌───────────── day of the week (0 - 6 or SUN-SAT)
│ │ │ │ │                                   
│ │ │ │ │
│ │ │ │ │
* * * * *
```