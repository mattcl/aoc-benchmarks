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
| `aspidites-solver/aoc -i input-aspidites -d 4` | 24.4 ± 4.0 | 22.0 | 34.7 | 20.19 ± 7.29 |
| `aspidites-solver/aoc -i input-kcen -d 4` | 25.2 ± 4.9 | 21.6 | 36.0 | 20.79 ± 7.85 |
| `aspidites-solver/aoc -i input-lanjian -d 4` | 24.2 ± 3.8 | 21.6 | 35.7 | 19.97 ± 7.16 |
| `aspidites-solver/aoc -i input-mattcl -d 4` | 24.6 ± 3.9 | 22.0 | 35.0 | 20.30 ± 7.31 |
| `aspidites-solver/aoc -i input-pting -d 4` | 25.1 ± 4.6 | 21.6 | 39.7 | 20.77 ± 7.72 |
| `kcen/2022/04/solve input-aspidites` | 3.0 ± 0.8 | 1.7 | 9.0 | 2.45 ± 1.06 |
| `kcen/2022/04/solve input-kcen` | 3.4 ± 1.3 | 1.9 | 11.1 | 2.84 ± 1.41 |
| `kcen/2022/04/solve input-lanjian` | 3.5 ± 1.9 | 1.7 | 21.2 | 2.86 ± 1.85 |
| `kcen/2022/04/solve input-mattcl` | 3.3 ± 0.9 | 1.8 | 7.0 | 2.74 ± 1.14 |
| `kcen/2022/04/solve input-pting` | 3.0 ± 1.0 | 1.8 | 18.6 | 2.46 ± 1.17 |
| `lanjian/day_04 input-aspidites` | 1.6 ± 0.8 | 0.7 | 8.6 | 1.35 ± 0.78 |
| `lanjian/day_04 input-kcen` | 1.3 ± 0.4 | 0.7 | 4.5 | 1.09 ± 0.51 |
| `lanjian/day_04 input-lanjian` | 1.2 ± 0.4 | 0.7 | 3.5 | 1.00 |
| `lanjian/day_04 input-mattcl` | 1.6 ± 0.6 | 0.7 | 5.7 | 1.28 ± 0.63 |
| `lanjian/day_04 input-pting` | 1.9 ± 0.9 | 0.8 | 8.4 | 1.57 ± 0.91 |
| `mattcl-solver/aoc run 4 input-aspidites` | 1.9 ± 0.6 | 0.8 | 4.7 | 1.60 ± 0.74 |
| `mattcl-solver/aoc run 4 input-kcen` | 2.0 ± 0.8 | 0.8 | 5.8 | 1.68 ± 0.86 |
| `mattcl-solver/aoc run 4 input-lanjian` | 1.6 ± 0.6 | 0.8 | 4.9 | 1.29 ± 0.66 |
| `mattcl-solver/aoc run 4 input-mattcl` | 1.6 ± 0.6 | 0.9 | 6.0 | 1.33 ± 0.64 |
| `mattcl-solver/aoc run 4 input-pting` | 1.8 ± 0.7 | 0.8 | 5.6 | 1.50 ± 0.77 |
| `python pting/day04.py input-aspidites` | 40.9 ± 11.5 | 30.6 | 99.5 | 33.80 ± 14.48 |
| `python pting/day04.py input-kcen` | 39.3 ± 8.5 | 28.1 | 63.3 | 32.46 ± 12.61 |
| `python pting/day04.py input-lanjian` | 39.4 ± 14.1 | 28.7 | 85.4 | 32.54 ± 15.66 |
| `python pting/day04.py input-mattcl` | 40.0 ± 7.8 | 31.5 | 67.7 | 33.04 ± 12.46 |
| `python pting/day04.py input-pting` | 39.8 ± 7.8 | 30.0 | 71.9 | 32.88 ± 12.40 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>500</pre>|<pre>815</pre>|
|input-mattcl|<pre>494</pre>|<pre>833</pre>|
|input-aspidites|<pre>569</pre>|<pre>936</pre>|
|input-pting|<pre>485</pre>|<pre>857</pre>|
|input-kcen|<pre>588</pre>|<pre>911</pre>|
