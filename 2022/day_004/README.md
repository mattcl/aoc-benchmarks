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
| `aspidites-solver/aoc -i input-aspidites -d 4` | 21.2 ± 5.7 | 12.7 | 31.7 | 9.26 ± 5.33 |
| `aspidites-solver/aoc -i input-kcen -d 4` | 19.2 ± 5.8 | 12.9 | 41.1 | 8.39 ± 4.97 |
| `aspidites-solver/aoc -i input-lanjian -d 4` | 23.5 ± 5.7 | 13.4 | 37.1 | 10.26 ± 5.79 |
| `aspidites-solver/aoc -i input-mattcl -d 4` | 19.2 ± 5.7 | 12.8 | 32.4 | 8.37 ± 4.94 |
| `aspidites-solver/aoc -i input-pting -d 4` | 19.0 ± 5.7 | 12.9 | 30.9 | 8.28 ± 4.90 |
| `kcen/2022/04/solve input-aspidites` | 4.4 ± 1.5 | 2.1 | 12.5 | 1.90 ± 1.16 |
| `kcen/2022/04/solve input-kcen` | 3.9 ± 1.1 | 1.9 | 10.9 | 1.70 ± 0.99 |
| `kcen/2022/04/solve input-lanjian` | 4.2 ± 1.4 | 2.0 | 20.2 | 1.83 ± 1.11 |
| `kcen/2022/04/solve input-mattcl` | 4.0 ± 2.0 | 1.5 | 24.2 | 1.73 ± 1.23 |
| `kcen/2022/04/solve input-pting` | 4.6 ± 1.5 | 2.4 | 11.7 | 2.02 ± 1.21 |
| `lanjian/day_04 input-aspidites` | 2.8 ± 1.1 | 0.8 | 8.8 | 1.22 ± 0.78 |
| `lanjian/day_04 input-kcen` | 2.8 ± 1.2 | 0.6 | 7.5 | 1.24 ± 0.81 |
| `lanjian/day_04 input-lanjian` | 2.4 ± 1.2 | 0.6 | 10.2 | 1.05 ± 0.75 |
| `lanjian/day_04 input-mattcl` | 3.2 ± 1.4 | 0.9 | 14.5 | 1.41 ± 0.95 |
| `lanjian/day_04 input-pting` | 3.3 ± 2.1 | 0.8 | 22.5 | 1.43 ± 1.19 |
| `mattcl-solver/aoc run 4 input-aspidites` | 5.8 ± 9.0 | 1.0 | 115.8 | 2.52 ± 4.14 |
| `mattcl-solver/aoc run 4 input-kcen` | 2.6 ± 1.0 | 0.6 | 9.5 | 1.15 ± 0.73 |
| `mattcl-solver/aoc run 4 input-lanjian` | 2.3 ± 1.2 | 0.4 | 7.8 | 1.00 |
| `mattcl-solver/aoc run 4 input-mattcl` | 2.8 ± 1.2 | 0.8 | 7.7 | 1.23 ± 0.81 |
| `mattcl-solver/aoc run 4 input-pting` | 2.6 ± 1.1 | 0.6 | 14.0 | 1.12 ± 0.75 |
| `python pting/day04.py input-aspidites` | 60.1 ± 9.6 | 45.7 | 81.7 | 26.27 ± 14.04 |
| `python pting/day04.py input-kcen` | 48.0 ± 7.7 | 38.1 | 72.8 | 20.95 ± 11.20 |
| `python pting/day04.py input-lanjian` | 53.7 ± 8.4 | 42.4 | 75.4 | 23.45 ± 12.50 |
| `python pting/day04.py input-mattcl` | 56.9 ± 8.9 | 44.8 | 78.4 | 24.85 ± 13.25 |
| `python pting/day04.py input-pting` | 64.5 ± 13.4 | 44.8 | 97.2 | 28.16 ± 15.51 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>500</pre>|<pre>815</pre>|
|input-mattcl|<pre>494</pre>|<pre>833</pre>|
|input-aspidites|<pre>569</pre>|<pre>936</pre>|
|input-pting|<pre>485</pre>|<pre>857</pre>|
|input-kcen|<pre>588</pre>|<pre>911</pre>|
