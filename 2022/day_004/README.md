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
| `aspidites-solver/aoc -i input-aspidites -d 4` | 23.6 ± 4.7 | 13.2 | 38.1 | 12.01 ± 7.01 |
| `aspidites-solver/aoc -i input-kcen -d 4` | 26.6 ± 4.3 | 13.1 | 42.8 | 13.57 ± 7.76 |
| `aspidites-solver/aoc -i input-lanjian -d 4` | 26.7 ± 4.1 | 13.6 | 40.8 | 13.58 ± 7.74 |
| `aspidites-solver/aoc -i input-mattcl -d 4` | 21.5 ± 5.7 | 12.8 | 38.9 | 10.94 ± 6.67 |
| `aspidites-solver/aoc -i input-pting -d 4` | 22.4 ± 5.1 | 12.9 | 29.0 | 11.41 ± 6.77 |
| `kcen/2022/04/solve input-aspidites` | 4.2 ± 1.3 | 1.9 | 10.7 | 2.16 ± 1.35 |
| `kcen/2022/04/solve input-kcen` | 5.3 ± 1.9 | 2.3 | 21.8 | 2.69 ± 1.77 |
| `kcen/2022/04/solve input-lanjian` | 4.6 ± 1.5 | 2.2 | 15.4 | 2.37 ± 1.50 |
| `kcen/2022/04/solve input-mattcl` | 4.4 ± 1.6 | 1.9 | 13.1 | 2.23 ± 1.48 |
| `kcen/2022/04/solve input-pting` | 7.2 ± 6.6 | 2.2 | 50.6 | 3.68 ± 3.93 |
| `lanjian/day_04 input-aspidites` | 3.1 ± 1.2 | 1.2 | 10.1 | 1.58 ± 1.06 |
| `lanjian/day_04 input-kcen` | 3.1 ± 1.4 | 0.7 | 11.0 | 1.55 ± 1.12 |
| `lanjian/day_04 input-lanjian` | 2.5 ± 1.5 | 0.6 | 15.0 | 1.27 ± 1.04 |
| `lanjian/day_04 input-mattcl` | 3.1 ± 1.3 | 0.9 | 9.3 | 1.56 ± 1.08 |
| `lanjian/day_04 input-pting` | 2.0 ± 1.1 | 0.3 | 7.7 | 1.00 |
| `mattcl-solver/aoc run 4 input-aspidites` | 2.8 ± 1.5 | 0.2 | 16.1 | 1.44 ± 1.10 |
| `mattcl-solver/aoc run 4 input-kcen` | 3.0 ± 1.3 | 0.6 | 11.0 | 1.52 ± 1.05 |
| `mattcl-solver/aoc run 4 input-lanjian` | 4.6 ± 4.9 | 0.4 | 50.2 | 2.36 ± 2.83 |
| `mattcl-solver/aoc run 4 input-mattcl` | 2.3 ± 1.1 | 0.4 | 8.0 | 1.19 ± 0.87 |
| `mattcl-solver/aoc run 4 input-pting` | 2.5 ± 1.4 | 0.6 | 22.6 | 1.27 ± 1.00 |
| `python pting/day04.py input-aspidites` | 71.1 ± 13.8 | 53.4 | 117.2 | 36.24 ± 21.09 |
| `python pting/day04.py input-kcen` | 69.4 ± 11.3 | 53.3 | 126.4 | 35.35 ± 20.23 |
| `python pting/day04.py input-lanjian` | 70.3 ± 16.5 | 54.3 | 135.0 | 35.81 ± 21.37 |
| `python pting/day04.py input-mattcl` | 72.3 ± 26.6 | 53.8 | 198.7 | 36.84 ± 24.34 |
| `python pting/day04.py input-pting` | 63.3 ± 11.6 | 48.0 | 119.5 | 32.22 ± 18.64 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>500</pre>|<pre>815</pre>|
|input-mattcl|<pre>494</pre>|<pre>833</pre>|
|input-aspidites|<pre>569</pre>|<pre>936</pre>|
|input-pting|<pre>485</pre>|<pre>857</pre>|
|input-kcen|<pre>588</pre>|<pre>911</pre>|
