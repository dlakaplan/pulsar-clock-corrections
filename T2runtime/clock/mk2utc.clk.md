
## Meerkat (TEMPO2)

MeerKAT clock corrections file (TEMPO2)

This file is pulled from the TEMPO2 repository and may not be fully up-to-date.

|     |     |
|:--- |:--- |
| File | `T2runtime/clock/mk2utc.clk` |
| Authority | temporary |
| URL in repository | <https://raw.githubusercontent.com/ipta/pulsar-clock-corrections/main/T2runtime/clock/mk2utc.clk> |
| Original download URL | <https://bitbucket.org/psrsoft/tempo2/raw/HEAD/T2runtime/clock/mk2utc.clk> |
| Format | tempo2 |
| Bogus last correction | True |
| Clock file start | 2019-01-01 MJD 58484.0 |
| Clock file end | 2021-02-22 MJD 59268.0 |
| Update interval (days) | 7 |
| Last update attempt | 2022-11-09 |
| Last update result | Unchanged |

Log entries from the last few update attempts:
```
2022-09-07 20:40:08.550 - Unchanged
2022-09-14 20:39:54.819 - Unchanged
2022-09-21 20:38:54.732 - Unchanged
2022-09-28 20:41:29.302 - Unchanged
2022-10-05 20:42:19.128 - Unchanged
2022-10-12 20:43:19.322 - Unchanged
2022-10-19 20:43:40.600 - Unchanged
2022-10-26 20:37:23.023 - Unchanged
2022-11-02 20:34:14.261 - Unchanged
2022-11-09 20:34:51.283 - Unchanged
```
[Full log](https://raw.githubusercontent.com/ipta/pulsar-clock-corrections/main/log/T2runtime/clock/mk2utc.clk.log)

Leading comments from clock file:

    # Tie of Karoo Telescope Time to UTC
    # This file is from the KTT-GNSS sensor, and does not include circular-T
    # MJD = (SensorTime(us)/86400e6)+40587    15-minute snapshots
    # Created at unix time 1614080015.929991 from KTT mySQL database.
    #
    # MJD (days)   KTT-UTC (seconds)
    #------------------------------------------------------



All clock corrections:

![plot of all clock corrections](mk2utc.clk.png "All corrections")

Recent clock corrections:

![plot of recent clock corrections](mk2utc.clk.short.png "Recent corrections")
