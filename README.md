An elegant way to use Todoist to build new habits

It integrates "Don't Break the Chain" method for habit building into [todoist](http://todoist.com/). Once it's setup, you can forget about it and it works seamlessly.  

<!-- ![Todoist Task Screenshot](https://i.imgur.com/HbWw5tu.jpeg?style=centerme) -->
<p align="center">
    <img width="300"  src="https://i.imgur.com/HbWw5tu.jpeg"/>
</p>

![Create a new task](https://i.imgur.com/9Ld5dvb.png)
## Usage

1. You add habits you want to form as task on todoist with schedule `every day`


2. Add `[day 0]` to the task

3. When you complete the task, the [day 0] will become [day 1]

4. If you fail to complete the task and it becomes overdue, the script will schedule it to today and reset [day X] to [day 0].

## Setup Instructions
1. You will need a GitHub account to setup this for your use. Please signup from [here](https://github.com/join) if you don't have an account yet. 

2. Clone or Fork the repo

3. Copy Todoist API key for your account from `Settings > Integrations` from [here](https://todoist.com/prefs/integrations).  

4. Add Todoist API key as a new secret to github action with `TODOIST_APIKEY`

5. Go to the `Actions` and click Run job button. In the future the task will run every day automatically. 

6. If everything is setup correctly, the streak on the tasks will automatically increase/decrease on the next day.

