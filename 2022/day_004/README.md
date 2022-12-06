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
| `aspidites-solver/aoc -i input-aspidites -d 4` | 27.6 ± 16.7 | 13.3 | 76.8 | 9.48 ± 6.81 |
| `aspidites-solver/aoc -i input-kcen -d 4` | 32.5 ± 11.8 | 25.0 | 91.7 | 11.15 ± 5.93 |
| `aspidites-solver/aoc -i input-lanjian -d 4` | 21.6 ± 5.1 | 13.3 | 31.2 | 7.43 ± 3.38 |
| `aspidites-solver/aoc -i input-mattcl -d 4` | 26.6 ± 4.4 | 14.5 | 47.2 | 9.12 ± 3.85 |
| `aspidites-solver/aoc -i input-pting -d 4` | 29.0 ± 11.2 | 13.6 | 85.7 | 9.96 ± 5.45 |
| `kcen/2022/04/solve input-aspidites` | 5.3 ± 1.7 | 2.6 | 16.1 | 1.83 ± 0.93 |
| `kcen/2022/04/solve input-kcen` | 8.1 ± 5.7 | 2.6 | 67.8 | 2.79 ± 2.23 |
| `kcen/2022/04/solve input-lanjian` | 4.7 ± 1.3 | 2.7 | 16.4 | 1.61 ± 0.77 |
| `kcen/2022/04/solve input-mattcl` | 5.4 ± 1.5 | 2.5 | 11.4 | 1.86 ± 0.88 |
| `kcen/2022/04/solve input-pting` | 5.8 ± 2.0 | 3.1 | 21.4 | 1.98 ± 1.02 |
| `lanjian/day_04 input-aspidites` | 3.4 ± 1.3 | 1.2 | 14.6 | 1.15 ± 0.63 |
| `lanjian/day_04 input-kcen` | 4.2 ± 1.9 | 1.5 | 20.5 | 1.45 ± 0.85 |
| `lanjian/day_04 input-lanjian` | 4.1 ± 1.5 | 1.3 | 12.5 | 1.42 ± 0.76 |
| `lanjian/day_04 input-mattcl` | 3.3 ± 1.2 | 1.3 | 9.4 | 1.12 ± 0.61 |
| `lanjian/day_04 input-pting` | 4.1 ± 1.3 | 1.6 | 11.4 | 1.40 ± 0.71 |
| `mattcl-solver/aoc run 4 input-aspidites` | 3.9 ± 1.1 | 1.6 | 9.5 | 1.36 ± 0.65 |
| `mattcl-solver/aoc run 4 input-kcen` | 4.6 ± 2.4 | 1.6 | 21.8 | 1.59 ± 1.04 |
| `mattcl-solver/aoc run 4 input-lanjian` | 4.0 ± 1.7 | 1.3 | 24.0 | 1.37 ± 0.79 |
| `mattcl-solver/aoc run 4 input-mattcl` | 2.9 ± 1.1 | 1.3 | 15.2 | 1.00 |
| `mattcl-solver/aoc run 4 input-pting` | 4.3 ± 4.1 | 1.4 | 46.2 | 1.47 ± 1.50 |
| `python pting/day04.py input-aspidites` | 67.0 ± 6.9 | 51.3 | 84.2 | 23.02 ± 9.25 |
| `python pting/day04.py input-kcen` | 90.6 ± 19.7 | 53.9 | 138.6 | 31.12 ± 13.85 |
| `python pting/day04.py input-lanjian` | 64.3 ± 9.1 | 50.5 | 84.9 | 22.09 ± 9.14 |
| `python pting/day04.py input-mattcl` | 70.9 ± 9.5 | 53.7 | 93.8 | 24.35 ± 10.01 |
| `python pting/day04.py input-pting` | 68.9 ± 8.6 | 55.4 | 100.3 | 23.67 ± 9.66 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>500</pre>|<pre>815</pre>|
|input-mattcl|<pre>494</pre>|<pre>833</pre>|
|input-aspidites|<pre>569</pre>|<pre>936</pre>|
|input-pting|<pre>485</pre>|<pre>857</pre>|
|input-kcen|<pre>588</pre>|<pre>911</pre>|
