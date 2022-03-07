# Employee-meeting-availability--Python
With a given list of Employee Meeting schedules, generate a list of maximum available time to schedule new meetings with maximum available employees on top.

Input: empSchedules=[["00:00-03:30","05:30-07:30"],["00:00-05:00"],["09:00-11:00","14:00-15:30"],["17:30-23:30"]]

Output: 
['11:00-14:00', 4]
['15:30-17:30', 4]
['07:30-09:00', 4]
['05:00-05:30', 4]
['23:30-24:00', 4]
['07:30-17:30', 3]
['15:30-24:00', 3]
['05:00-09:00', 3]
['03:30-05:30', 3]
['07:30-24:00', 2]
['05:00-17:30', 2]
['00:00-09:00', 2]
['05:00-24:00', 1]
['00:00-17:30', 1]
['00:00-24:00', 0]
