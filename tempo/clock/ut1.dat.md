
## UT1 table

UT1 table

This file records the Earth's actual rotation in the form of
corrections TAI-UT1 in a format readable by TEMPO.

This file is generated from Astropy's parsing of the IERS
bulletins. It should be updated approximately monthly, and it
includes the IERS predictions covering about a year after the
publication date.

This differs slightly from the version traditionally distributed
with TEMPO - that is generated by a combination of a perl script
parsing the output from the IERS web form and a custom C program
generating predictions. As a result, this generated file may not
extend as far into the future as the conventional ut1.dat does.
There are also minor differences in some of the early values; the
origin of these early values is not completely clear, and some of
them predate the earliest values in the IERS bulletins Astropy uses.

If there are any questions, contact Anne Archibald
<anne.archibald@newcastle.ac.uk>.

|     |     |
|:--- |:--- |
| File | `tempo/clock/ut1.dat` |
| Authority | observatory |
| File start | 1973-01-02 MJD 41684.0 |
| File end | 2023-11-18 MJD 60266.0 |
| Update interval (days) | 0 |
| Last update attempt | 2022-11-11 |
| Last update result | Unchanged |

Log entries from the last few update attempts:
```
2022-11-02 20:34:25.370 - Unchanged
2022-11-03 20:29:02.697 - Updated
2022-11-04 20:36:50.815 - Unchanged
2022-11-05 20:35:49.505 - Unchanged
2022-11-06 20:33:56.016 - Unchanged
2022-11-07 20:36:16.070 - Unchanged
2022-11-08 20:36:28.717 - Unchanged
2022-11-09 20:34:59.759 - Unchanged
2022-11-10 20:36:10.888 - Updated
2022-11-11 20:35:03.375 - Unchanged
```
[Full log](https://raw.githubusercontent.com/ipta/pulsar-clock-corrections/main/log/tempo/clock/ut1.dat.log)