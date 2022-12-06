# Day 4 benchmarks

[link to problem](http://adventofcode.com/2022/day/4)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

[ci pipeline](http://ci.papercode.net:8080/teams/aoc2022/pipelines/aoc-compare-2022)

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Repos (with solutions for day 4)


- [aspidites](https://github.com/aspidites/aoc2022)
- [kcen](https://github.com/kcen/AdventOfCode)
- [lanjian](https://github.com/LanJian/aoc-2022)
- [mattcl](https://github.com/mattcl/aoc2022)
- [pting](https://github.com/pting/aoc2022)

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `aspidites-solver/aoc -i input-aspidites -d 4` | 23.4 ± 5.1 | 12.6 | 39.0 | 13.40 ± 8.55 |
| `aspidites-solver/aoc -i input-kcen -d 4` | 18.9 ± 6.0 | 12.2 | 35.0 | 10.85 ± 7.34 |
| `aspidites-solver/aoc -i input-lanjian -d 4` | 20.2 ± 5.6 | 12.2 | 27.8 | 11.54 ± 7.61 |
| `aspidites-solver/aoc -i input-mattcl -d 4` | 17.3 ± 5.6 | 12.1 | 27.8 | 9.92 ± 6.75 |
| `aspidites-solver/aoc -i input-pting -d 4` | 19.7 ± 5.6 | 12.4 | 30.8 | 11.28 ± 7.47 |
| `kcen/2022/04/solve input-aspidites` | 4.2 ± 1.4 | 1.6 | 12.6 | 2.38 ± 1.64 |
| `kcen/2022/04/solve input-kcen` | 3.3 ± 1.0 | 1.5 | 8.0 | 1.87 ± 1.25 |
| `kcen/2022/04/solve input-lanjian` | 3.3 ± 1.3 | 1.2 | 14.5 | 1.91 ± 1.35 |
| `kcen/2022/04/solve input-mattcl` | 3.6 ± 1.0 | 1.6 | 7.3 | 2.04 ± 1.35 |
| `kcen/2022/04/solve input-pting` | 4.0 ± 1.5 | 1.4 | 14.8 | 2.30 ± 1.62 |
| `lanjian/day_04 input-aspidites` | 2.1 ± 1.3 | 0.2 | 12.1 | 1.23 ± 1.06 |
| `lanjian/day_04 input-kcen` | 2.2 ± 1.2 | 0.3 | 12.2 | 1.26 ± 1.01 |
| `lanjian/day_04 input-lanjian` | 1.8 ± 1.0 | 0.2 | 8.9 | 1.02 ± 0.85 |
| `lanjian/day_04 input-mattcl` | 2.1 ± 1.0 | 0.1 | 7.4 | 1.20 ± 0.91 |
| `lanjian/day_04 input-pting` | 2.5 ± 0.9 | 0.8 | 6.4 | 1.44 ± 1.01 |
| `mattcl-solver/aoc run 4 input-aspidites` | 1.7 ± 1.0 | 0.0 | 10.2 | 1.00 |
| `mattcl-solver/aoc run 4 input-kcen` | 1.8 ± 1.0 | 0.2 | 12.6 | 1.01 ± 0.85 |
| `mattcl-solver/aoc run 4 input-lanjian` | 2.5 ± 1.3 | 0.0 | 10.9 | 1.41 ± 1.12 |
| `mattcl-solver/aoc run 4 input-mattcl` | 2.3 ± 1.6 | 0.2 | 31.0 | 1.33 ± 1.24 |
| `mattcl-solver/aoc run 4 input-pting` | 2.9 ± 1.3 | 0.5 | 13.1 | 1.68 ± 1.26 |
| `python pting/day04.py input-aspidites` | 65.6 ± 9.2 | 48.5 | 86.6 | 37.57 ± 23.11 |
| `python pting/day04.py input-kcen` | 65.3 ± 9.2 | 51.5 | 90.0 | 37.37 ± 22.99 |
| `python pting/day04.py input-lanjian` | 62.8 ± 6.8 | 53.4 | 85.4 | 35.93 ± 21.86 |
| `python pting/day04.py input-mattcl` | 78.1 ± 24.2 | 48.4 | 139.3 | 44.69 ± 30.12 |
| `python pting/day04.py input-pting` | 65.2 ± 9.4 | 47.6 | 91.7 | 37.34 ± 23.00 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>500</pre>|<pre>815</pre>|
|input-mattcl|<pre>494</pre>|<pre>833</pre>|
|input-aspidites|<pre>569</pre>|<pre>936</pre>|
|input-pting|<pre>485</pre>|<pre>857</pre>|
|input-kcen|<pre>588</pre>|<pre>911</pre>|
