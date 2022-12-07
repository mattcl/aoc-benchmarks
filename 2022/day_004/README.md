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
| `aspidites-solver/aoc -i input-aspidites -d 4` | 22.3 ± 6.8 | 13.1 | 56.1 | 8.94 ± 4.76 |
| `aspidites-solver/aoc -i input-kcen -d 4` | 21.9 ± 5.5 | 13.7 | 32.5 | 8.79 ± 4.42 |
| `aspidites-solver/aoc -i input-lanjian -d 4` | 21.8 ± 17.0 | 13.1 | 184.6 | 8.73 ± 7.82 |
| `aspidites-solver/aoc -i input-mattcl -d 4` | 22.2 ± 6.5 | 13.3 | 46.7 | 8.89 ± 4.67 |
| `aspidites-solver/aoc -i input-pting -d 4` | 20.1 ± 5.9 | 13.2 | 37.8 | 8.04 ± 4.24 |
| `kcen/2022/04/solve input-aspidites` | 4.4 ± 1.4 | 2.2 | 12.1 | 1.77 ± 0.96 |
| `kcen/2022/04/solve input-kcen` | 5.2 ± 1.7 | 2.1 | 24.8 | 2.10 ± 1.15 |
| `kcen/2022/04/solve input-lanjian` | 8.5 ± 7.4 | 2.4 | 47.1 | 3.43 ± 3.34 |
| `kcen/2022/04/solve input-mattcl` | 4.6 ± 1.1 | 2.4 | 7.5 | 1.86 ± 0.92 |
| `kcen/2022/04/solve input-pting` | 4.4 ± 1.2 | 2.1 | 10.6 | 1.75 ± 0.91 |
| `lanjian/day_04 input-aspidites` | 2.8 ± 1.3 | 1.1 | 15.3 | 1.11 ± 0.72 |
| `lanjian/day_04 input-kcen` | 3.2 ± 1.6 | 1.0 | 14.6 | 1.30 ± 0.85 |
| `lanjian/day_04 input-lanjian` | 2.5 ± 1.1 | 0.6 | 14.0 | 1.00 |
| `lanjian/day_04 input-mattcl` | 3.6 ± 1.6 | 1.0 | 19.0 | 1.42 ± 0.90 |
| `lanjian/day_04 input-pting` | 3.6 ± 2.9 | 1.1 | 57.1 | 1.44 ± 1.31 |
| `mattcl-solver/aoc run 4 input-aspidites` | 3.6 ± 2.1 | 1.0 | 14.2 | 1.46 ± 1.07 |
| `mattcl-solver/aoc run 4 input-kcen` | 3.0 ± 1.1 | 1.0 | 14.4 | 1.19 ± 0.69 |
| `mattcl-solver/aoc run 4 input-lanjian` | 3.0 ± 1.2 | 1.1 | 11.7 | 1.21 ± 0.71 |
| `mattcl-solver/aoc run 4 input-mattcl` | 3.3 ± 1.4 | 1.1 | 14.3 | 1.33 ± 0.82 |
| `mattcl-solver/aoc run 4 input-pting` | 3.3 ± 1.6 | 1.1 | 12.9 | 1.33 ± 0.85 |
| `python pting/day04.py input-aspidites` | 53.5 ± 8.0 | 41.9 | 83.9 | 21.44 ± 9.89 |
| `python pting/day04.py input-kcen` | 86.6 ± 44.9 | 47.1 | 238.6 | 34.70 ± 23.52 |
| `python pting/day04.py input-lanjian` | 56.2 ± 7.2 | 45.2 | 73.8 | 22.53 ± 10.26 |
| `python pting/day04.py input-mattcl` | 55.7 ± 7.9 | 46.9 | 83.0 | 22.34 ± 10.25 |
| `python pting/day04.py input-pting` | 54.5 ± 8.3 | 44.8 | 93.9 | 21.83 ± 10.11 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>500</pre>|<pre>815</pre>|
|input-mattcl|<pre>494</pre>|<pre>833</pre>|
|input-aspidites|<pre>569</pre>|<pre>936</pre>|
|input-pting|<pre>485</pre>|<pre>857</pre>|
|input-kcen|<pre>588</pre>|<pre>911</pre>|
