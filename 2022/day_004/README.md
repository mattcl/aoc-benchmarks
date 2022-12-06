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
| `aspidites-solver/aoc -i input-aspidites -d 4` | 23.7 ± 6.9 | 12.6 | 43.5 | 15.61 ± 14.00 |
| `aspidites-solver/aoc -i input-kcen -d 4` | 20.3 ± 6.8 | 11.8 | 45.1 | 13.41 ± 12.21 |
| `aspidites-solver/aoc -i input-lanjian -d 4` | 27.3 ± 6.6 | 12.7 | 46.7 | 18.01 ± 15.89 |
| `aspidites-solver/aoc -i input-mattcl -d 4` | 19.8 ± 7.0 | 12.2 | 40.3 | 13.06 ± 12.01 |
| `aspidites-solver/aoc -i input-pting -d 4` | 22.6 ± 7.3 | 12.6 | 43.5 | 14.90 ± 13.52 |
| `kcen/2022/04/solve input-aspidites` | 3.9 ± 2.1 | 1.2 | 15.7 | 2.57 ± 2.58 |
| `kcen/2022/04/solve input-kcen` | 4.4 ± 1.8 | 1.5 | 12.3 | 2.87 ± 2.69 |
| `kcen/2022/04/solve input-lanjian` | 4.8 ± 1.9 | 1.6 | 10.2 | 3.14 ± 2.94 |
| `kcen/2022/04/solve input-mattcl` | 4.3 ± 2.2 | 1.0 | 15.6 | 2.84 ± 2.79 |
| `kcen/2022/04/solve input-pting` | 4.6 ± 2.2 | 1.5 | 19.4 | 3.06 ± 2.96 |
| `lanjian/day_04 input-aspidites` | 2.0 ± 1.3 | 0.0 | 13.1 | 1.29 ± 1.39 |
| `lanjian/day_04 input-kcen` | 1.5 ± 1.3 | 0.1 | 7.5 | 1.00 |
| `lanjian/day_04 input-lanjian` | 2.0 ± 1.4 | 0.0 | 12.3 | 1.34 ± 1.46 |
| `lanjian/day_04 input-mattcl` | 2.6 ± 1.7 | 0.0 | 13.9 | 1.68 ± 1.83 |
| `lanjian/day_04 input-pting` | 2.0 ± 1.8 | 0.0 | 15.1 | 1.29 ± 1.62 |
| `mattcl-solver/aoc run 4 input-aspidites` | 4.3 ± 5.0 | 0.0 | 36.8 | 2.86 ± 4.11 |
| `mattcl-solver/aoc run 4 input-kcen` | 2.8 ± 1.7 | 0.1 | 13.6 | 1.86 ± 1.94 |
| `mattcl-solver/aoc run 4 input-lanjian` | 1.6 ± 1.2 | 0.0 | 7.2 | 1.04 ± 1.19 |
| `mattcl-solver/aoc run 4 input-mattcl` | 2.6 ± 3.0 | 0.1 | 45.2 | 1.69 ± 2.46 |
| `mattcl-solver/aoc run 4 input-pting` | 2.5 ± 1.8 | 0.1 | 15.4 | 1.67 ± 1.83 |
| `python pting/day04.py input-aspidites` | 69.6 ± 29.4 | 46.2 | 187.0 | 45.84 ± 43.44 |
| `python pting/day04.py input-kcen` | 65.0 ± 22.6 | 44.6 | 162.6 | 42.85 ± 39.27 |
| `python pting/day04.py input-lanjian` | 72.0 ± 28.3 | 47.2 | 169.3 | 47.43 ± 44.34 |
| `python pting/day04.py input-mattcl` | 65.2 ± 26.1 | 44.3 | 189.0 | 42.98 ± 40.30 |
| `python pting/day04.py input-pting` | 62.3 ± 19.4 | 47.4 | 142.9 | 41.08 ± 37.12 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>500</pre>|<pre>815</pre>|
|input-mattcl|<pre>494</pre>|<pre>833</pre>|
|input-aspidites|<pre>569</pre>|<pre>936</pre>|
|input-pting|<pre>485</pre>|<pre>857</pre>|
|input-kcen|<pre>588</pre>|<pre>911</pre>|
