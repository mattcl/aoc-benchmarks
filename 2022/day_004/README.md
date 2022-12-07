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
| `aspidites-solver/aoc -i input-aspidites -d 4` | 31.5 ± 27.1 | 13.6 | 226.8 | 11.01 ± 10.16 |
| `aspidites-solver/aoc -i input-kcen -d 4` | 20.0 ± 5.8 | 13.5 | 35.9 | 6.98 ± 3.10 |
| `aspidites-solver/aoc -i input-lanjian -d 4` | 19.1 ± 5.4 | 13.6 | 32.2 | 6.69 ± 2.94 |
| `aspidites-solver/aoc -i input-mattcl -d 4` | 23.0 ± 6.3 | 13.9 | 43.9 | 8.03 ± 3.48 |
| `aspidites-solver/aoc -i input-pting -d 4` | 21.1 ± 5.7 | 13.7 | 35.9 | 7.37 ± 3.18 |
| `kcen/2022/04/solve input-aspidites` | 4.8 ± 1.3 | 2.5 | 11.5 | 1.67 ± 0.71 |
| `kcen/2022/04/solve input-kcen` | 4.9 ± 1.5 | 2.2 | 13.9 | 1.72 ± 0.77 |
| `kcen/2022/04/solve input-lanjian` | 5.2 ± 1.7 | 2.4 | 20.1 | 1.83 ± 0.86 |
| `kcen/2022/04/solve input-mattcl` | 6.7 ± 3.0 | 3.0 | 27.0 | 2.35 ± 1.30 |
| `kcen/2022/04/solve input-pting` | 4.9 ± 1.6 | 2.6 | 13.4 | 1.71 ± 0.81 |
| `lanjian/day_04 input-aspidites` | 3.4 ± 1.2 | 1.2 | 12.0 | 1.20 ± 0.58 |
| `lanjian/day_04 input-kcen` | 3.8 ± 1.4 | 1.5 | 15.5 | 1.32 ± 0.66 |
| `lanjian/day_04 input-lanjian` | 3.5 ± 1.4 | 1.2 | 13.4 | 1.21 ± 0.62 |
| `lanjian/day_04 input-mattcl` | 2.9 ± 1.0 | 1.1 | 10.5 | 1.00 |
| `lanjian/day_04 input-pting` | 3.5 ± 1.3 | 1.5 | 12.3 | 1.24 ± 0.62 |
| `mattcl-solver/aoc run 4 input-aspidites` | 3.5 ± 1.3 | 1.3 | 10.3 | 1.23 ± 0.60 |
| `mattcl-solver/aoc run 4 input-kcen` | 3.3 ± 1.2 | 1.1 | 12.1 | 1.15 ± 0.57 |
| `mattcl-solver/aoc run 4 input-lanjian` | 2.9 ± 1.1 | 1.2 | 7.8 | 1.01 ± 0.51 |
| `mattcl-solver/aoc run 4 input-mattcl` | 3.1 ± 1.4 | 1.1 | 14.1 | 1.09 ± 0.63 |
| `mattcl-solver/aoc run 4 input-pting` | 3.1 ± 1.3 | 1.0 | 13.9 | 1.07 ± 0.57 |
| `python pting/day04.py input-aspidites` | 55.6 ± 7.4 | 44.8 | 82.5 | 19.43 ± 7.02 |
| `python pting/day04.py input-kcen` | 61.5 ± 9.6 | 48.7 | 89.1 | 21.48 ± 7.95 |
| `python pting/day04.py input-lanjian` | 56.0 ± 6.9 | 44.9 | 74.9 | 19.57 ± 7.00 |
| `python pting/day04.py input-mattcl` | 59.1 ± 11.2 | 42.2 | 83.7 | 20.65 ± 7.97 |
| `python pting/day04.py input-pting` | 61.5 ± 9.9 | 48.1 | 84.9 | 21.50 ± 8.00 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>500</pre>|<pre>815</pre>|
|input-mattcl|<pre>494</pre>|<pre>833</pre>|
|input-aspidites|<pre>569</pre>|<pre>936</pre>|
|input-pting|<pre>485</pre>|<pre>857</pre>|
|input-kcen|<pre>588</pre>|<pre>911</pre>|
