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
| `aspidites-solver/aoc -i input-aspidites -d 4` | 24.8 ± 4.5 | 21.5 | 43.7 | 21.40 ± 11.33 |
| `aspidites-solver/aoc -i input-kcen -d 4` | 23.3 ± 3.4 | 21.5 | 43.2 | 20.09 ± 10.42 |
| `aspidites-solver/aoc -i input-lanjian -d 4` | 25.3 ± 5.0 | 21.6 | 44.0 | 21.82 ± 11.69 |
| `aspidites-solver/aoc -i input-mattcl -d 4` | 27.9 ± 6.0 | 21.9 | 44.4 | 24.13 ± 13.07 |
| `aspidites-solver/aoc -i input-pting -d 4` | 23.9 ± 4.1 | 21.5 | 45.5 | 20.60 ± 10.85 |
| `kcen/2022/04/solve input-aspidites` | 2.9 ± 1.3 | 1.4 | 8.6 | 2.54 ± 1.66 |
| `kcen/2022/04/solve input-kcen` | 3.3 ± 2.3 | 1.7 | 29.8 | 2.83 ± 2.46 |
| `kcen/2022/04/solve input-lanjian` | 3.0 ± 1.4 | 1.5 | 8.1 | 2.63 ± 1.78 |
| `kcen/2022/04/solve input-mattcl` | 3.6 ± 1.2 | 1.9 | 8.8 | 3.09 ± 1.85 |
| `kcen/2022/04/solve input-pting` | 2.7 ± 1.1 | 1.5 | 6.3 | 2.35 ± 1.48 |
| `lanjian/day_04 input-aspidites` | 1.7 ± 1.0 | 0.6 | 8.9 | 1.50 ± 1.13 |
| `lanjian/day_04 input-kcen` | 1.2 ± 0.5 | 0.7 | 7.0 | 1.07 ± 0.68 |
| `lanjian/day_04 input-lanjian` | 1.7 ± 0.9 | 0.6 | 8.3 | 1.47 ± 1.05 |
| `lanjian/day_04 input-mattcl` | 2.1 ± 1.0 | 0.5 | 12.6 | 1.82 ± 1.23 |
| `lanjian/day_04 input-pting` | 1.6 ± 0.8 | 0.6 | 6.4 | 1.39 ± 0.96 |
| `mattcl-solver/aoc run 4 input-aspidites` | 1.7 ± 0.9 | 0.3 | 11.7 | 1.47 ± 1.07 |
| `mattcl-solver/aoc run 4 input-kcen` | 1.2 ± 0.6 | 0.4 | 7.3 | 1.00 |
| `mattcl-solver/aoc run 4 input-lanjian` | 1.8 ± 0.7 | 0.6 | 4.8 | 1.59 ± 1.02 |
| `mattcl-solver/aoc run 4 input-mattcl` | 1.9 ± 0.8 | 0.6 | 6.9 | 1.68 ± 1.08 |
| `mattcl-solver/aoc run 4 input-pting` | 1.2 ± 0.7 | 0.5 | 11.1 | 1.06 ± 0.80 |
| `python pting/day04.py input-aspidites` | 41.9 ± 9.6 | 29.5 | 77.4 | 36.16 ± 19.80 |
| `python pting/day04.py input-kcen` | 37.1 ± 10.6 | 29.2 | 99.7 | 32.03 ± 18.37 |
| `python pting/day04.py input-lanjian` | 40.2 ± 10.9 | 29.1 | 75.5 | 34.69 ± 19.67 |
| `python pting/day04.py input-mattcl` | 38.7 ± 9.9 | 28.2 | 75.2 | 33.44 ± 18.71 |
| `python pting/day04.py input-pting` | 38.8 ± 7.2 | 29.2 | 59.2 | 33.53 ± 17.79 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>500</pre>|<pre>815</pre>|
|input-mattcl|<pre>494</pre>|<pre>833</pre>|
|input-aspidites|<pre>569</pre>|<pre>936</pre>|
|input-pting|<pre>485</pre>|<pre>857</pre>|
|input-kcen|<pre>588</pre>|<pre>911</pre>|
