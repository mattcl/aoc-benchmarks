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
| `aspidites-solver/aoc -i input-aspidites -d 4` | 24.2 ± 4.3 | 12.9 | 37.0 | 10.93 ± 5.73 |
| `aspidites-solver/aoc -i input-kcen -d 4` | 25.1 ± 3.4 | 13.4 | 37.3 | 11.34 ± 5.80 |
| `aspidites-solver/aoc -i input-lanjian -d 4` | 23.3 ± 5.7 | 12.1 | 42.7 | 10.54 ± 5.80 |
| `aspidites-solver/aoc -i input-mattcl -d 4` | 24.8 ± 6.0 | 12.9 | 50.4 | 11.19 ± 6.15 |
| `aspidites-solver/aoc -i input-pting -d 4` | 26.7 ± 6.0 | 13.5 | 56.0 | 12.09 ± 6.55 |
| `kcen/2022/04/solve input-aspidites` | 5.1 ± 2.0 | 2.2 | 16.3 | 2.32 ± 1.47 |
| `kcen/2022/04/solve input-kcen` | 4.6 ± 1.6 | 2.0 | 22.6 | 2.08 ± 1.27 |
| `kcen/2022/04/solve input-lanjian` | 5.4 ± 2.7 | 1.8 | 22.5 | 2.45 ± 1.71 |
| `kcen/2022/04/solve input-mattcl` | 5.6 ± 2.7 | 2.3 | 17.6 | 2.52 ± 1.74 |
| `kcen/2022/04/solve input-pting` | 5.5 ± 2.4 | 2.3 | 23.4 | 2.47 ± 1.64 |
| `lanjian/day_04 input-aspidites` | 2.2 ± 1.1 | 0.6 | 8.7 | 1.00 |
| `lanjian/day_04 input-kcen` | 3.3 ± 1.7 | 0.6 | 10.6 | 1.50 ± 1.05 |
| `lanjian/day_04 input-lanjian` | 2.7 ± 1.5 | 0.3 | 16.8 | 1.21 ± 0.90 |
| `lanjian/day_04 input-mattcl` | 3.4 ± 1.8 | 1.0 | 15.0 | 1.54 ± 1.10 |
| `lanjian/day_04 input-pting` | 3.6 ± 1.8 | 0.8 | 13.5 | 1.61 ± 1.15 |
| `mattcl-solver/aoc run 4 input-aspidites` | 3.0 ± 1.4 | 1.0 | 13.5 | 1.34 ± 0.92 |
| `mattcl-solver/aoc run 4 input-kcen` | 3.4 ± 1.9 | 0.8 | 14.1 | 1.55 ± 1.15 |
| `mattcl-solver/aoc run 4 input-lanjian` | 3.1 ± 1.5 | 0.7 | 11.1 | 1.41 ± 0.96 |
| `mattcl-solver/aoc run 4 input-mattcl` | 3.1 ± 1.6 | 0.5 | 12.2 | 1.42 ± 1.00 |
| `mattcl-solver/aoc run 4 input-pting` | 3.4 ± 1.5 | 0.9 | 11.0 | 1.53 ± 1.00 |
| `python pting/day04.py input-aspidites` | 70.7 ± 19.1 | 52.7 | 168.6 | 31.97 ± 17.99 |
| `python pting/day04.py input-kcen` | 62.7 ± 18.6 | 45.4 | 177.5 | 28.37 ± 16.32 |
| `python pting/day04.py input-lanjian` | 69.9 ± 17.2 | 50.4 | 158.3 | 31.59 ± 17.43 |
| `python pting/day04.py input-mattcl` | 70.7 ± 6.4 | 56.7 | 89.8 | 31.96 ± 16.04 |
| `python pting/day04.py input-pting` | 90.3 ± 54.6 | 53.9 | 329.3 | 40.84 ± 31.87 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>500</pre>|<pre>815</pre>|
|input-mattcl|<pre>494</pre>|<pre>833</pre>|
|input-aspidites|<pre>569</pre>|<pre>936</pre>|
|input-pting|<pre>485</pre>|<pre>857</pre>|
|input-kcen|<pre>588</pre>|<pre>911</pre>|
