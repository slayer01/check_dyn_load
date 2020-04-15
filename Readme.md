# check_dyn_load

This check determines cpu cores by counting the string 'processors' from proc/cpuinfo

and calls the nagios-plugin check_load with load thresholds calculated beforehand.
