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
| `aspidites-solver/aoc -i input-aspidites -d 4` | 16.5 ± 5.1 | 12.1 | 34.2 | 12.67 ± 9.09 |
| `aspidites-solver/aoc -i input-kcen -d 4` | 20.3 ± 6.1 | 12.3 | 36.3 | 15.59 ± 11.12 |
| `aspidites-solver/aoc -i input-lanjian -d 4` | 17.9 ± 6.0 | 12.1 | 39.0 | 13.74 ± 10.03 |
| `aspidites-solver/aoc -i input-mattcl -d 4` | 17.2 ± 5.1 | 12.4 | 27.8 | 13.17 ± 9.40 |
| `aspidites-solver/aoc -i input-pting -d 4` | 20.3 ± 7.1 | 12.7 | 55.4 | 15.54 ± 11.47 |
| `kcen/2022/04/solve input-aspidites` | 3.2 ± 1.2 | 1.4 | 10.5 | 2.46 ± 1.84 |
| `kcen/2022/04/solve input-kcen` | 3.3 ± 1.3 | 1.2 | 9.4 | 2.54 ± 1.91 |
| `kcen/2022/04/solve input-lanjian` | 2.9 ± 1.5 | 1.2 | 10.4 | 2.25 ± 1.84 |
| `kcen/2022/04/solve input-mattcl` | 3.8 ± 1.4 | 1.5 | 10.7 | 2.89 ± 2.15 |
| `kcen/2022/04/solve input-pting` | 3.9 ± 1.4 | 1.7 | 15.2 | 2.99 ± 2.23 |
| `lanjian/day_04 input-aspidites` | 2.1 ± 1.7 | 0.2 | 18.3 | 1.62 ± 1.66 |
| `lanjian/day_04 input-kcen` | 1.8 ± 0.9 | 0.2 | 8.6 | 1.35 ± 1.14 |
| `lanjian/day_04 input-lanjian` | 1.6 ± 1.0 | 0.1 | 9.5 | 1.25 ± 1.14 |
| `lanjian/day_04 input-mattcl` | 1.3 ± 0.9 | 0.1 | 11.2 | 1.03 ± 0.99 |
| `lanjian/day_04 input-pting` | 1.6 ± 1.1 | 0.1 | 11.1 | 1.25 ± 1.14 |
| `mattcl-solver/aoc run 4 input-aspidites` | 1.8 ± 1.2 | 0.0 | 8.2 | 1.36 ± 1.26 |
| `mattcl-solver/aoc run 4 input-kcen` | 4.3 ± 4.7 | 0.1 | 40.0 | 3.32 ± 4.21 |
| `mattcl-solver/aoc run 4 input-lanjian` | 1.3 ± 0.8 | 0.2 | 4.8 | 1.00 |
| `mattcl-solver/aoc run 4 input-mattcl` | 1.5 ± 0.9 | 0.0 | 5.5 | 1.12 ± 0.99 |
| `mattcl-solver/aoc run 4 input-pting` | 1.6 ± 1.1 | 0.2 | 10.0 | 1.26 ± 1.16 |
| `python pting/day04.py input-aspidites` | 54.9 ± 9.7 | 41.5 | 92.0 | 42.11 ± 28.29 |
| `python pting/day04.py input-kcen` | 55.9 ± 11.9 | 43.6 | 106.1 | 42.86 ± 29.24 |
| `python pting/day04.py input-lanjian` | 70.1 ± 22.3 | 43.1 | 153.0 | 53.82 ± 38.84 |
| `python pting/day04.py input-mattcl` | 51.7 ± 7.4 | 42.5 | 82.6 | 39.66 ± 26.31 |
| `python pting/day04.py input-pting` | 54.7 ± 7.2 | 43.9 | 74.1 | 41.97 ± 27.74 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>500</pre>|<pre>815</pre>|
|input-mattcl|<pre>494</pre>|<pre>833</pre>|
|input-aspidites|<pre>569</pre>|<pre>936</pre>|
|input-pting|<pre>485</pre>|<pre>857</pre>|
|input-kcen|<pre>588</pre>|<pre>911</pre>|
