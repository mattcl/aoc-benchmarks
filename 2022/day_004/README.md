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
| `aspidites-solver/aoc -i input-aspidites -d 4` | 22.5 ± 7.7 | 13.0 | 66.9 | 8.66 ± 5.93 |
| `aspidites-solver/aoc -i input-kcen -d 4` | 22.5 ± 5.9 | 13.2 | 37.3 | 8.66 ± 5.62 |
| `aspidites-solver/aoc -i input-lanjian -d 4` | 18.9 ± 5.7 | 13.2 | 35.7 | 7.27 ± 4.84 |
| `aspidites-solver/aoc -i input-mattcl -d 4` | 19.9 ± 5.7 | 13.1 | 28.3 | 7.67 ± 5.06 |
| `aspidites-solver/aoc -i input-pting -d 4` | 22.3 ± 5.8 | 12.8 | 36.6 | 8.58 ± 5.56 |
| `kcen/2022/04/solve input-aspidites` | 5.4 ± 1.8 | 2.3 | 23.1 | 2.06 ± 1.40 |
| `kcen/2022/04/solve input-kcen` | 5.9 ± 2.3 | 2.8 | 23.9 | 2.29 ± 1.62 |
| `kcen/2022/04/solve input-lanjian` | 5.1 ± 1.7 | 1.6 | 15.7 | 1.96 ± 1.33 |
| `kcen/2022/04/solve input-mattcl` | 5.2 ± 1.5 | 2.5 | 10.9 | 2.02 ± 1.32 |
| `kcen/2022/04/solve input-pting` | 4.1 ± 1.5 | 2.0 | 16.8 | 1.58 ± 1.09 |
| `lanjian/day_04 input-aspidites` | 3.0 ± 1.2 | 0.9 | 12.6 | 1.15 ± 0.83 |
| `lanjian/day_04 input-kcen` | 2.8 ± 1.5 | 0.8 | 22.9 | 1.08 ± 0.87 |
| `lanjian/day_04 input-lanjian` | 2.9 ± 1.5 | 0.8 | 19.8 | 1.13 ± 0.88 |
| `lanjian/day_04 input-mattcl` | 3.3 ± 1.6 | 1.0 | 18.1 | 1.25 ± 0.97 |
| `lanjian/day_04 input-pting` | 2.6 ± 1.5 | 0.7 | 13.8 | 1.00 |
| `mattcl-solver/aoc run 4 input-aspidites` | 3.0 ± 1.2 | 0.7 | 10.1 | 1.14 ± 0.82 |
| `mattcl-solver/aoc run 4 input-kcen` | 2.9 ± 1.3 | 0.5 | 9.0 | 1.12 ± 0.83 |
| `mattcl-solver/aoc run 4 input-lanjian` | 3.2 ± 1.5 | 0.6 | 15.3 | 1.25 ± 0.93 |
| `mattcl-solver/aoc run 4 input-mattcl` | 3.4 ± 1.9 | 0.5 | 28.5 | 1.33 ± 1.09 |
| `mattcl-solver/aoc run 4 input-pting` | 2.6 ± 1.6 | 0.6 | 18.5 | 1.01 ± 0.85 |
| `python pting/day04.py input-aspidites` | 66.5 ± 10.2 | 48.9 | 88.7 | 25.62 ± 15.69 |
| `python pting/day04.py input-kcen` | 55.5 ± 10.5 | 43.8 | 94.8 | 21.41 ± 13.33 |
| `python pting/day04.py input-lanjian` | 57.7 ± 8.0 | 44.3 | 76.7 | 22.24 ± 13.54 |
| `python pting/day04.py input-mattcl` | 61.3 ± 11.9 | 42.4 | 93.8 | 23.62 ± 14.73 |
| `python pting/day04.py input-pting` | 57.0 ± 10.2 | 45.1 | 89.0 | 21.98 ± 13.61 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>500</pre>|<pre>815</pre>|
|input-mattcl|<pre>494</pre>|<pre>833</pre>|
|input-aspidites|<pre>569</pre>|<pre>936</pre>|
|input-pting|<pre>485</pre>|<pre>857</pre>|
|input-kcen|<pre>588</pre>|<pre>911</pre>|
