# Converting-timestamp-to-time-ago-in-PHP-e.g-1-day-ago-2-days-ago

**Use example :**

echo time_elapsed_string('2015-05-01 00:22:35');

echo time_elapsed_string('@1467367755'); # timestamp input

echo time_elapsed_string('2015-05-01 00:22:35', true);

Input can be any supported date and time format.

**Output :**

4 months ago

4 months ago

4 months, 2 weeks, 3 days, 1 hour, 49 minutes, 15 seconds ago
