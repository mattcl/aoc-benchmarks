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
| `aspidites-solver/aoc -i input-aspidites -d 4` | 22.9 ± 5.1 | 12.4 | 36.3 | 11.37 ± 7.78 |
| `aspidites-solver/aoc -i input-kcen -d 4` | 27.8 ± 4.3 | 13.3 | 45.8 | 13.84 ± 9.21 |
| `aspidites-solver/aoc -i input-lanjian -d 4` | 26.3 ± 6.8 | 12.7 | 54.8 | 13.09 ± 9.13 |
| `aspidites-solver/aoc -i input-mattcl -d 4` | 24.8 ± 4.9 | 13.1 | 46.0 | 12.34 ± 8.36 |
| `aspidites-solver/aoc -i input-pting -d 4` | 26.6 ± 6.4 | 12.7 | 52.5 | 13.23 ± 9.14 |
| `kcen/2022/04/solve input-aspidites` | 4.5 ± 1.6 | 1.5 | 15.5 | 2.24 ± 1.67 |
| `kcen/2022/04/solve input-kcen` | 6.0 ± 3.2 | 2.3 | 26.5 | 3.01 ± 2.53 |
| `kcen/2022/04/solve input-lanjian` | 4.7 ± 1.7 | 1.8 | 14.3 | 2.33 ± 1.74 |
| `kcen/2022/04/solve input-mattcl` | 4.4 ± 1.9 | 1.4 | 17.8 | 2.21 ± 1.73 |
| `kcen/2022/04/solve input-pting` | 9.0 ± 9.5 | 1.9 | 72.8 | 4.49 ± 5.57 |
| `lanjian/day_04 input-aspidites` | 3.0 ± 2.3 | 0.2 | 19.2 | 1.51 ± 1.49 |
| `lanjian/day_04 input-kcen` | 3.1 ± 1.9 | 0.0 | 18.1 | 1.53 ± 1.37 |
| `lanjian/day_04 input-lanjian` | 4.3 ± 5.4 | 0.0 | 40.3 | 2.14 ± 3.04 |
| `lanjian/day_04 input-mattcl` | 3.3 ± 2.0 | 0.7 | 20.9 | 1.65 ± 1.44 |
| `lanjian/day_04 input-pting` | 2.0 ± 1.3 | 0.0 | 9.1 | 1.00 |
| `mattcl-solver/aoc run 4 input-aspidites` | 2.6 ± 1.7 | 0.0 | 21.9 | 1.29 ± 1.17 |
| `mattcl-solver/aoc run 4 input-kcen` | 3.1 ± 2.2 | 0.5 | 24.7 | 1.54 ± 1.48 |
| `mattcl-solver/aoc run 4 input-lanjian` | 2.3 ± 1.6 | 0.0 | 11.3 | 1.16 ± 1.08 |
| `mattcl-solver/aoc run 4 input-mattcl` | 2.8 ± 1.5 | 0.4 | 10.3 | 1.39 ± 1.18 |
| `mattcl-solver/aoc run 4 input-pting` | 2.4 ± 2.2 | 0.0 | 46.9 | 1.21 ± 1.36 |
| `python pting/day04.py input-aspidites` | 68.2 ± 11.7 | 48.1 | 97.3 | 33.94 ± 22.74 |
| `python pting/day04.py input-kcen` | 67.5 ± 10.4 | 49.4 | 88.2 | 33.55 ± 22.33 |
| `python pting/day04.py input-lanjian` | 64.5 ± 10.2 | 47.0 | 101.4 | 32.06 ± 21.38 |
| `python pting/day04.py input-mattcl` | 66.7 ± 11.5 | 47.6 | 95.3 | 33.15 ± 22.22 |
| `python pting/day04.py input-pting` | 65.3 ± 14.5 | 44.9 | 107.8 | 32.48 ± 22.25 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>500</pre>|<pre>815</pre>|
|input-mattcl|<pre>494</pre>|<pre>833</pre>|
|input-aspidites|<pre>569</pre>|<pre>936</pre>|
|input-pting|<pre>485</pre>|<pre>857</pre>|
|input-kcen|<pre>588</pre>|<pre>911</pre>|
