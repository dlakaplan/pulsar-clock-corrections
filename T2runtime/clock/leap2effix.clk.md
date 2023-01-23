
## LEAP

LEAP clock correction file

This file corrects from the LEAP clock to the Effelsberg Asterix
clock; then the effix2gps file can be used to convert to GPS.

This file is pulled from the TEMPO2 repository and may not be fully
up-to-date. The European Pulsar Timing Array maintains an internal
repository of clock corrections, which they have transferred to the TEMPO2
repository, so  EPTA telescope data in the TEMPO2 repository (and
thus here) can be expected to be somewhat up to date.

|     |     |
|:--- |:--- |
| File | `T2runtime/clock/leap2effix.clk` |
| Authority | temporary |
| URL in repository | <https://raw.githubusercontent.com/ipta/pulsar-clock-corrections/main/T2runtime/clock/leap2effix.clk> |
| Original download URL | <https://bitbucket.org/psrsoft/tempo2/raw/HEAD/T2runtime/clock/leap2effix.clk> |
| Format | tempo2 |
| Bogus last correction | True |
| Clock file start | 2012-10-29 MJD 56230.0 |
| Clock file end | 2014-03-04 MJD 56720.0 |
| Update interval (days) | 7 |
| Last update attempt | 2023-01-20 |
| Last update result | Unchanged |

Log entries from the last few update attempts:
```
2022-12-23 14:04:34.573 - Unchanged
2022-12-30 20:27:23.304 - Unchanged
2023-01-06 20:28:37.372 - Unchanged
2023-01-13 20:29:25.143 - Unchanged
2023-01-20 20:28:55.383 - Unchanged
```
[Full log](https://raw.githubusercontent.com/ipta/pulsar-clock-corrections/main/log/T2runtime/clock/leap2effix.clk.log)

Leading comments from clock file:

    # Some 'effix' time jumps do not appear in LEAP data
    # So we must account for this...
    #    MJD: 56230 to 56490; offset=-0.0972843 s * pre-removed in LEAP
    #    MJD: 56490 to 56720; offset=-0.409268 s * pre-removed in LEAP
    #



All clock corrections:

![plot of all clock corrections](leap2effix.clk.png "All corrections")

Recent clock corrections:

![plot of recent clock corrections](leap2effix.clk.short.png "Recent corrections")
