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
| `aspidites-solver/aoc -i input-aspidites -d 4` | 35.0 ± 5.5 | 31.9 | 55.3 | 25.26 ± 8.76 |
| `aspidites-solver/aoc -i input-kcen -d 4` | 41.6 ± 9.0 | 32.0 | 64.1 | 30.05 ± 11.36 |
| `aspidites-solver/aoc -i input-lanjian -d 4` | 35.9 ± 5.4 | 32.0 | 56.1 | 25.88 ± 8.91 |
| `aspidites-solver/aoc -i input-mattcl -d 4` | 33.5 ± 3.7 | 31.9 | 55.6 | 24.16 ± 7.95 |
| `aspidites-solver/aoc -i input-pting -d 4` | 41.0 ± 9.0 | 32.2 | 64.8 | 29.59 ± 11.23 |
| `kcen/2022/04/solve input-aspidites` | 3.0 ± 1.0 | 2.0 | 8.7 | 2.14 ± 0.97 |
| `kcen/2022/04/solve input-kcen` | 3.6 ± 1.1 | 2.0 | 7.4 | 2.56 ± 1.14 |
| `kcen/2022/04/solve input-lanjian` | 3.0 ± 1.1 | 1.8 | 13.6 | 2.16 ± 1.05 |
| `kcen/2022/04/solve input-mattcl` | 2.3 ± 0.6 | 1.8 | 5.5 | 1.69 ± 0.68 |
| `kcen/2022/04/solve input-pting` | 3.0 ± 1.4 | 1.8 | 16.2 | 2.19 ± 1.24 |
| `lanjian/day_04 input-aspidites` | 1.6 ± 0.5 | 0.8 | 4.2 | 1.14 ± 0.49 |
| `lanjian/day_04 input-kcen` | 1.4 ± 0.5 | 0.9 | 11.7 | 1.00 ± 0.50 |
| `lanjian/day_04 input-lanjian` | 1.4 ± 0.5 | 0.8 | 4.6 | 1.03 ± 0.47 |
| `lanjian/day_04 input-mattcl` | 1.4 ± 0.5 | 0.9 | 6.0 | 1.05 ± 0.49 |
| `lanjian/day_04 input-pting` | 1.8 ± 0.6 | 0.9 | 5.0 | 1.28 ± 0.58 |
| `mattcl-solver/aoc run 4 input-aspidites` | 1.4 ± 0.4 | 0.9 | 4.9 | 1.00 |
| `mattcl-solver/aoc run 4 input-kcen` | 1.7 ± 0.6 | 1.0 | 5.6 | 1.25 ± 0.59 |
| `mattcl-solver/aoc run 4 input-lanjian` | 1.5 ± 0.5 | 0.9 | 4.4 | 1.06 ± 0.48 |
| `mattcl-solver/aoc run 4 input-mattcl` | 1.5 ± 0.4 | 1.0 | 3.7 | 1.11 ± 0.43 |
| `mattcl-solver/aoc run 4 input-pting` | 2.2 ± 0.8 | 1.2 | 11.7 | 1.58 ± 0.76 |
| `python pting/day04.py input-aspidites` | 39.4 ± 9.1 | 30.5 | 75.1 | 28.41 ± 10.97 |
| `python pting/day04.py input-kcen` | 37.3 ± 6.4 | 29.8 | 57.7 | 26.96 ± 9.55 |
| `python pting/day04.py input-lanjian` | 39.4 ± 6.3 | 32.1 | 66.0 | 28.46 ± 9.93 |
| `python pting/day04.py input-mattcl` | 38.5 ± 7.6 | 29.3 | 68.0 | 27.80 ± 10.23 |
| `python pting/day04.py input-pting` | 39.2 ± 10.5 | 29.2 | 108.1 | 28.33 ± 11.58 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>500</pre>|<pre>815</pre>|
|input-mattcl|<pre>494</pre>|<pre>833</pre>|
|input-aspidites|<pre>569</pre>|<pre>936</pre>|
|input-pting|<pre>485</pre>|<pre>857</pre>|
|input-kcen|<pre>588</pre>|<pre>911</pre>|
