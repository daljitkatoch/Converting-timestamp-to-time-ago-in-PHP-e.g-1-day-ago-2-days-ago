# Converting-timestamp-to-time-ago-in-PHP-e.g-1-day-ago-2-days-ago

**Use example :**

echo time_elapsed_string('2015-05-01 00:22:35');

echo time_elapsed_string('@1467367755'); # timestamp input

echo time_elapsed_string('2015-05-01 00:22:35', true);

Input can be any supported date and time format.

**Output :**

5 years ago

4 years ago

5 years, 11 months, 3 weeks, 5 days, 5 hours, 48 minutes, 18 seconds ago
