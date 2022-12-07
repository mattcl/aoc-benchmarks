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
| `aspidites-solver/aoc -i input-aspidites -d 4` | 21.2 ± 6.1 | 12.7 | 36.6 | 9.55 ± 6.17 |
| `aspidites-solver/aoc -i input-kcen -d 4` | 22.8 ± 5.2 | 12.7 | 36.6 | 10.26 ± 6.38 |
| `aspidites-solver/aoc -i input-lanjian -d 4` | 22.3 ± 6.0 | 13.0 | 51.1 | 10.04 ± 6.40 |
| `aspidites-solver/aoc -i input-mattcl -d 4` | 24.5 ± 5.0 | 12.9 | 39.2 | 11.03 ± 6.76 |
| `aspidites-solver/aoc -i input-pting -d 4` | 22.1 ± 7.1 | 12.8 | 49.5 | 9.95 ± 6.58 |
| `kcen/2022/04/solve input-aspidites` | 4.9 ± 3.8 | 1.9 | 30.1 | 2.19 ± 2.13 |
| `kcen/2022/04/solve input-kcen` | 5.5 ± 2.1 | 2.3 | 19.5 | 2.46 ± 1.71 |
| `kcen/2022/04/solve input-lanjian` | 4.7 ± 1.9 | 2.0 | 26.3 | 2.10 ± 1.50 |
| `kcen/2022/04/solve input-mattcl` | 4.8 ± 2.1 | 1.7 | 20.2 | 2.15 ± 1.55 |
| `kcen/2022/04/solve input-pting` | 5.1 ± 2.4 | 2.3 | 32.5 | 2.29 ± 1.72 |
| `lanjian/day_04 input-aspidites` | 2.4 ± 1.2 | 0.3 | 10.4 | 1.07 ± 0.83 |
| `lanjian/day_04 input-kcen` | 2.7 ± 1.3 | 0.4 | 12.7 | 1.23 ± 0.92 |
| `lanjian/day_04 input-lanjian` | 2.2 ± 1.3 | 0.2 | 8.9 | 1.00 |
| `lanjian/day_04 input-mattcl` | 2.9 ± 1.6 | 0.2 | 13.6 | 1.30 ± 1.03 |
| `lanjian/day_04 input-pting` | 3.7 ± 2.2 | 0.5 | 20.8 | 1.65 ± 1.38 |
| `mattcl-solver/aoc run 4 input-aspidites` | 2.9 ± 1.4 | 0.4 | 15.5 | 1.30 ± 0.97 |
| `mattcl-solver/aoc run 4 input-kcen` | 2.5 ± 1.6 | 0.2 | 17.1 | 1.12 ± 0.96 |
| `mattcl-solver/aoc run 4 input-lanjian` | 2.3 ± 1.4 | 0.2 | 13.6 | 1.05 ± 0.88 |
| `mattcl-solver/aoc run 4 input-mattcl` | 2.5 ± 1.4 | 0.2 | 13.3 | 1.11 ± 0.89 |
| `mattcl-solver/aoc run 4 input-pting` | 5.5 ± 5.8 | 0.4 | 38.2 | 2.50 ± 2.98 |
| `python pting/day04.py input-aspidites` | 60.0 ± 9.7 | 47.8 | 94.2 | 27.04 ± 16.23 |
| `python pting/day04.py input-kcen` | 63.2 ± 12.4 | 47.1 | 98.1 | 28.49 ± 17.39 |
| `python pting/day04.py input-lanjian` | 59.8 ± 8.3 | 48.3 | 88.8 | 26.96 ± 16.03 |
| `python pting/day04.py input-mattcl` | 60.9 ± 10.1 | 48.9 | 96.3 | 27.43 ± 16.49 |
| `python pting/day04.py input-pting` | 66.6 ± 8.5 | 52.8 | 83.4 | 30.01 ± 17.76 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>500</pre>|<pre>815</pre>|
|input-mattcl|<pre>494</pre>|<pre>833</pre>|
|input-aspidites|<pre>569</pre>|<pre>936</pre>|
|input-pting|<pre>485</pre>|<pre>857</pre>|
|input-kcen|<pre>588</pre>|<pre>911</pre>|
