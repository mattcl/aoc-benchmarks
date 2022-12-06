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
| `lanjian/day_06 input-lanjian` | 2.5 ± 1.7 | 0.2 | 19.5 | 1.30 ± 1.20 |
| `lanjian/day_06 input-mattcl` | 1.9 ± 1.3 | 0.2 | 11.3 | 1.02 ± 0.95 |
| `lanjian/day_06 input-pting` | 1.9 ± 1.2 | 0.1 | 7.2 | 1.00 |
| `mattcl-solver/aoc run 6 input-lanjian` | 4.2 ± 1.2 | 1.9 | 12.1 | 2.20 ± 1.52 |
| `mattcl-solver/aoc run 6 input-mattcl` | 4.3 ± 1.8 | 1.8 | 20.6 | 2.27 ± 1.72 |
| `mattcl-solver/aoc run 6 input-pting` | 4.8 ± 1.4 | 2.0 | 11.0 | 2.55 ± 1.75 |
| `python pting/day06.py input-lanjian` | 68.5 ± 9.8 | 53.8 | 100.6 | 36.32 ± 23.13 |
| `python pting/day06.py input-mattcl` | 62.3 ± 7.5 | 51.6 | 86.2 | 33.05 ± 20.90 |
| `python pting/day06.py input-pting` | 59.7 ± 6.1 | 49.3 | 74.5 | 31.65 ± 19.91 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1623</pre>|<pre>3774</pre>|
|input-mattcl|<pre>1625</pre>|<pre>2250</pre>|
|input-pting|<pre>1802</pre>|<pre>3551</pre>|
