# Daily Time Manager

A tiny widget which helps users **maximize their time's value by making their productive time plans**.

## About

![Sample image][sample-img]

To begin with, users are required to **write down their daily tasks and the estimated time consumption of those tasks**. This tiny **widget will then calculate the total time consumed and the time left unconsumed**. In case the unconsumed time is negative or too long, or the productive time is unsatisfactory, a plan adjustment is needed. For instance, squeezing time from other tasks if the productive time is found to be unsatisfactory. After making a satisfactory time plan, a user will need to strictly follow the plan and adjust it if it is not executable or a better plan is found. Please note that a **detailed time plan is recommended** since it grants users **a clear view of their time allocation** and **avoids a waste of time of which they, in general, are not aware**. 

## Plan execution

A productive plan failing to execute is useless. Therefore, its execution is also very important. **Check [planExecutionTips.md][plan-execution-tips] for tips that may help execute a plan**.

## Usage

Steps:

1. Modify the object at the top level of the [HTML file][working-day-sample] to customize your time plan. 
2. Render the HTML file to view your time plan.
3. Repeat step(1) until the time plan becomes satisfactory.
4. Make a new copy of the [HTML file][working-day-sample] and repeat the above steps if another plan is wanted.

[plan-execution-tips]: planExecutionTips.md
[working-day-sample]: samples/workingDays.html
[sample-img]: docs/v0.0.0/screenshot.png
