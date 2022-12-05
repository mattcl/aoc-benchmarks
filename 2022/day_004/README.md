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
| `aspidites-solver/aoc -i input-aspidites -d 4` | 12.5 ± 1.6 | 11.6 | 28.3 | 11.44 ± 7.23 |
| `aspidites-solver/aoc -i input-kcen -d 4` | 12.5 ± 0.5 | 11.9 | 14.4 | 11.45 ± 7.11 |
| `aspidites-solver/aoc -i input-lanjian -d 4` | 12.7 ± 1.1 | 11.8 | 23.3 | 11.62 ± 7.27 |
| `aspidites-solver/aoc -i input-mattcl -d 4` | 12.6 ± 1.2 | 11.8 | 22.7 | 11.56 ± 7.24 |
| `aspidites-solver/aoc -i input-pting -d 4` | 12.6 ± 1.3 | 11.7 | 23.4 | 11.54 ± 7.24 |
| `kcen/2022/04/solve input-aspidites` | 2.5 ± 0.9 | 1.8 | 13.1 | 2.29 ± 1.64 |
| `kcen/2022/04/solve input-kcen` | 2.7 ± 0.6 | 1.8 | 9.4 | 2.43 ± 1.61 |
| `kcen/2022/04/solve input-lanjian` | 3.4 ± 1.0 | 1.8 | 13.5 | 3.10 ± 2.12 |
| `kcen/2022/04/solve input-mattcl` | 2.5 ± 0.6 | 1.7 | 7.9 | 2.26 ± 1.49 |
| `kcen/2022/04/solve input-pting` | 2.2 ± 0.6 | 1.8 | 9.7 | 2.06 ± 1.37 |
| `lanjian/day_04 input-aspidites` | 1.3 ± 0.3 | 0.8 | 3.2 | 1.21 ± 0.81 |
| `lanjian/day_04 input-kcen` | 1.6 ± 0.5 | 0.8 | 5.4 | 1.46 ± 1.00 |
| `lanjian/day_04 input-lanjian` | 1.5 ± 0.5 | 0.7 | 6.7 | 1.33 ± 0.93 |
| `lanjian/day_04 input-mattcl` | 1.5 ± 0.4 | 0.8 | 3.8 | 1.35 ± 0.91 |
| `lanjian/day_04 input-pting` | 1.1 ± 0.2 | 0.8 | 4.3 | 1.00 ± 0.66 |
| `mattcl-solver/aoc run 4 input-aspidites` | 1.4 ± 0.4 | 0.7 | 3.9 | 1.28 ± 0.89 |
| `mattcl-solver/aoc run 4 input-kcen` | 1.3 ± 0.4 | 0.8 | 6.7 | 1.22 ± 0.85 |
| `mattcl-solver/aoc run 4 input-lanjian` | 1.4 ± 0.4 | 0.7 | 3.8 | 1.29 ± 0.87 |
| `mattcl-solver/aoc run 4 input-mattcl` | 1.4 ± 0.4 | 0.8 | 4.1 | 1.32 ± 0.88 |
| `mattcl-solver/aoc run 4 input-pting` | 1.1 ± 0.7 | 0.7 | 12.3 | 1.00 |
| `python pting/day04.py input-aspidites` | 35.0 ± 4.7 | 29.6 | 53.5 | 32.03 ± 20.30 |
| `python pting/day04.py input-kcen` | 37.5 ± 3.9 | 32.5 | 49.7 | 34.31 ± 21.54 |
| `python pting/day04.py input-lanjian` | 38.7 ± 6.1 | 30.8 | 57.8 | 35.43 ± 22.65 |
| `python pting/day04.py input-mattcl` | 37.5 ± 3.9 | 32.4 | 48.0 | 34.30 ± 21.54 |
| `python pting/day04.py input-pting` | 34.0 ± 3.5 | 29.8 | 60.9 | 31.10 ± 19.53 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>500</pre>|<pre>815</pre>|
|input-mattcl|<pre>494</pre>|<pre>833</pre>|
|input-aspidites|<pre>569</pre>|<pre>936</pre>|
|input-pting|<pre>485</pre>|<pre>857</pre>|
|input-kcen|<pre>588</pre>|<pre>911</pre>|
