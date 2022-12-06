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
| `aspidites-solver/aoc -i input-aspidites -d 4` | 27.6 ± 6.9 | 13.0 | 58.1 | 12.17 ± 7.01 |
| `aspidites-solver/aoc -i input-kcen -d 4` | 20.9 ± 5.9 | 12.7 | 37.2 | 9.23 ± 5.45 |
| `aspidites-solver/aoc -i input-lanjian -d 4` | 26.5 ± 4.9 | 14.2 | 46.4 | 11.72 ± 6.46 |
| `aspidites-solver/aoc -i input-mattcl -d 4` | 21.8 ± 5.9 | 13.2 | 38.7 | 9.62 ± 5.63 |
| `aspidites-solver/aoc -i input-pting -d 4` | 22.3 ± 6.5 | 12.9 | 44.0 | 9.84 ± 5.86 |
| `kcen/2022/04/solve input-aspidites` | 5.4 ± 2.3 | 2.4 | 18.2 | 2.40 ± 1.61 |
| `kcen/2022/04/solve input-kcen` | 4.7 ± 2.6 | 2.0 | 20.0 | 2.08 ± 1.56 |
| `kcen/2022/04/solve input-lanjian` | 4.7 ± 1.4 | 2.1 | 14.5 | 2.09 ± 1.25 |
| `kcen/2022/04/solve input-mattcl` | 4.1 ± 1.8 | 1.8 | 15.4 | 1.80 ± 1.22 |
| `kcen/2022/04/solve input-pting` | 4.4 ± 1.5 | 2.3 | 16.1 | 1.96 ± 1.22 |
| `lanjian/day_04 input-aspidites` | 2.8 ± 1.7 | 0.5 | 15.3 | 1.25 ± 1.00 |
| `lanjian/day_04 input-kcen` | 2.3 ± 1.0 | 0.7 | 6.4 | 1.03 ± 0.71 |
| `lanjian/day_04 input-lanjian` | 3.3 ± 2.0 | 1.0 | 24.0 | 1.45 ± 1.15 |
| `lanjian/day_04 input-mattcl` | 3.0 ± 1.5 | 0.8 | 10.7 | 1.32 ± 0.95 |
| `lanjian/day_04 input-pting` | 3.6 ± 2.0 | 1.4 | 14.5 | 1.61 ± 1.22 |
| `mattcl-solver/aoc run 4 input-aspidites` | 2.5 ± 1.5 | 0.7 | 18.2 | 1.09 ± 0.86 |
| `mattcl-solver/aoc run 4 input-kcen` | 2.6 ± 1.2 | 0.9 | 11.2 | 1.14 ± 0.78 |
| `mattcl-solver/aoc run 4 input-lanjian` | 2.3 ± 1.2 | 0.7 | 12.9 | 1.00 |
| `mattcl-solver/aoc run 4 input-mattcl` | 2.9 ± 1.6 | 0.9 | 15.0 | 1.30 ± 0.97 |
| `mattcl-solver/aoc run 4 input-pting` | 3.9 ± 2.4 | 1.4 | 19.0 | 1.71 ± 1.38 |
| `python pting/day04.py input-aspidites` | 90.2 ± 44.3 | 47.0 | 263.0 | 39.84 ± 28.49 |
| `python pting/day04.py input-kcen` | 63.4 ± 11.7 | 48.8 | 120.7 | 28.01 ± 15.44 |
| `python pting/day04.py input-lanjian` | 62.1 ± 6.1 | 52.1 | 75.3 | 27.44 ± 14.50 |
| `python pting/day04.py input-mattcl` | 65.2 ± 19.7 | 49.5 | 143.6 | 28.79 ± 17.29 |
| `python pting/day04.py input-pting` | 60.8 ± 5.5 | 50.9 | 72.8 | 26.85 ± 14.16 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>500</pre>|<pre>815</pre>|
|input-mattcl|<pre>494</pre>|<pre>833</pre>|
|input-aspidites|<pre>569</pre>|<pre>936</pre>|
|input-pting|<pre>485</pre>|<pre>857</pre>|
|input-kcen|<pre>588</pre>|<pre>911</pre>|
