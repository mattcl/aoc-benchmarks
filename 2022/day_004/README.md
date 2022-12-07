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
| `aspidites-solver/aoc -i input-aspidites -d 4` | 19.5 ± 8.0 | 12.4 | 54.8 | 8.61 ± 7.39 |
| `aspidites-solver/aoc -i input-kcen -d 4` | 18.3 ± 7.8 | 12.0 | 41.0 | 8.10 ± 7.00 |
| `aspidites-solver/aoc -i input-lanjian -d 4` | 22.7 ± 8.2 | 13.1 | 45.7 | 10.05 ± 8.40 |
| `aspidites-solver/aoc -i input-mattcl -d 4` | 23.4 ± 9.1 | 12.5 | 75.1 | 10.35 ± 8.77 |
| `aspidites-solver/aoc -i input-pting -d 4` | 23.5 ± 7.3 | 13.4 | 42.7 | 10.39 ± 8.46 |
| `kcen/2022/04/solve input-aspidites` | 4.8 ± 2.1 | 1.5 | 17.1 | 2.12 ± 1.85 |
| `kcen/2022/04/solve input-kcen` | 4.4 ± 2.0 | 1.1 | 15.6 | 1.95 ± 1.70 |
| `kcen/2022/04/solve input-lanjian` | 5.0 ± 2.4 | 1.9 | 14.3 | 2.22 ± 1.97 |
| `kcen/2022/04/solve input-mattcl` | 5.1 ± 2.0 | 2.2 | 12.5 | 2.25 ± 1.91 |
| `kcen/2022/04/solve input-pting` | 4.9 ± 1.9 | 1.9 | 11.8 | 2.14 ± 1.82 |
| `lanjian/day_04 input-aspidites` | 2.5 ± 1.4 | 0.2 | 9.7 | 1.12 ± 1.04 |
| `lanjian/day_04 input-kcen` | 2.3 ± 1.7 | 0.0 | 11.0 | 1.00 |
| `lanjian/day_04 input-lanjian` | 3.3 ± 2.1 | 0.4 | 19.4 | 1.47 ± 1.45 |
| `lanjian/day_04 input-mattcl` | 3.2 ± 1.8 | 0.0 | 18.1 | 1.43 ± 1.33 |
| `lanjian/day_04 input-pting` | 5.7 ± 5.0 | 0.6 | 36.5 | 2.53 ± 2.91 |
| `mattcl-solver/aoc run 4 input-aspidites` | 3.2 ± 1.6 | 0.0 | 14.7 | 1.39 ± 1.27 |
| `mattcl-solver/aoc run 4 input-kcen` | 2.7 ± 1.8 | 0.0 | 14.3 | 1.20 ± 1.19 |
| `mattcl-solver/aoc run 4 input-lanjian` | 3.8 ± 1.9 | 0.0 | 13.2 | 1.66 ± 1.50 |
| `mattcl-solver/aoc run 4 input-mattcl` | 3.6 ± 1.7 | 0.6 | 17.3 | 1.61 ± 1.43 |
| `mattcl-solver/aoc run 4 input-pting` | 3.7 ± 2.3 | 0.5 | 26.7 | 1.63 ± 1.60 |
| `python pting/day04.py input-aspidites` | 53.0 ± 17.5 | 37.4 | 127.3 | 23.40 ± 19.23 |
| `python pting/day04.py input-kcen` | 56.8 ± 21.5 | 38.4 | 149.3 | 25.09 ± 21.15 |
| `python pting/day04.py input-lanjian` | 68.7 ± 31.3 | 45.0 | 165.2 | 30.34 ± 26.70 |
| `python pting/day04.py input-mattcl` | 74.3 ± 30.6 | 43.5 | 144.8 | 32.83 ± 28.18 |
| `python pting/day04.py input-pting` | 52.8 ± 17.8 | 39.3 | 138.6 | 23.35 ± 19.26 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>500</pre>|<pre>815</pre>|
|input-mattcl|<pre>494</pre>|<pre>833</pre>|
|input-aspidites|<pre>569</pre>|<pre>936</pre>|
|input-pting|<pre>485</pre>|<pre>857</pre>|
|input-kcen|<pre>588</pre>|<pre>911</pre>|
