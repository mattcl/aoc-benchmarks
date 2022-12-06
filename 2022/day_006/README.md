# Day 6 benchmarks

[link to problem](http://adventofcode.com/2022/day/6)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

[ci pipeline](http://ci.papercode.net:8080/teams/aoc2022/pipelines/aoc-compare-2022)

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Repos (with solutions for day 6)


- [lanjian](https://github.com/LanJian/aoc-2022)
- [mattcl](https://github.com/mattcl/aoc2022)
- [pting](https://github.com/pting/aoc2022)

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `lanjian/day_06 input-lanjian` | 2.6 ± 1.6 | 0.8 | 18.5 | 1.35 ± 1.33 |
| `lanjian/day_06 input-mattcl` | 2.2 ± 1.3 | 0.7 | 11.1 | 1.16 ± 1.13 |
| `lanjian/day_06 input-pting` | 1.9 ± 1.5 | 0.6 | 24.1 | 1.00 |
| `mattcl-solver/aoc run 6 input-lanjian` | 2.9 ± 1.3 | 0.8 | 9.9 | 1.50 ± 1.35 |
| `mattcl-solver/aoc run 6 input-mattcl` | 3.2 ± 1.2 | 1.1 | 10.2 | 1.63 ± 1.40 |
| `mattcl-solver/aoc run 6 input-pting` | 2.5 ± 1.3 | 1.0 | 14.4 | 1.30 ± 1.20 |
| `python pting/day06.py input-lanjian` | 50.6 ± 5.2 | 43.7 | 70.2 | 26.11 ± 20.24 |
| `python pting/day06.py input-mattcl` | 72.7 ± 29.3 | 47.2 | 162.4 | 37.55 ± 32.57 |
| `python pting/day06.py input-pting` | 58.7 ± 14.8 | 44.4 | 133.0 | 30.33 ± 24.52 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1623</pre>|<pre>3774</pre>|
|input-mattcl|<pre>1625</pre>|<pre>2250</pre>|
|input-pting|<pre>1802</pre>|<pre>3551</pre>|
