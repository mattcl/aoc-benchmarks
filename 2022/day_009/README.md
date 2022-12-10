# Day 9 benchmarks

[link to problem](http://adventofcode.com/2022/day/9)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

[ci pipeline](http://ci.papercode.net:8080/teams/aoc2022/pipelines/aoc-compare-2022)

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Repos (with solutions for day 9)


- [lanjian](https://github.com/LanJian/aoc-2022)
- [mattcl](https://github.com/mattcl/aoc2022)
- [pting](https://github.com/pting/aoc2022)

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `lanjian/day_09 input-lanjian` | 4.9 ± 1.6 | 2.9 | 19.9 | 1.35 ± 0.63 |
| `lanjian/day_09 input-mattcl` | 5.3 ± 2.0 | 2.8 | 17.8 | 1.45 ± 0.74 |
| `lanjian/day_09 input-pting` | 4.5 ± 1.4 | 2.2 | 12.3 | 1.25 ± 0.57 |
| `mattcl-solver/aoc run 9 input-lanjian` | 4.0 ± 1.1 | 2.0 | 17.5 | 1.10 ± 0.47 |
| `mattcl-solver/aoc run 9 input-mattcl` | 4.0 ± 1.2 | 2.0 | 11.2 | 1.12 ± 0.51 |
| `mattcl-solver/aoc run 9 input-pting` | 3.6 ± 1.2 | 1.8 | 16.1 | 1.00 |
| `python pting/day09.py input-lanjian` | 171.0 ± 19.4 | 150.4 | 228.2 | 47.13 ± 16.89 |
| `python pting/day09.py input-mattcl` | 162.6 ± 21.1 | 135.7 | 227.6 | 44.83 ± 16.30 |
| `python pting/day09.py input-pting` | 156.3 ± 11.4 | 143.0 | 182.8 | 43.08 ± 14.97 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>5907</pre>|<pre>2303</pre>|
|input-mattcl|<pre>6057</pre>|<pre>2514</pre>|
|input-pting|<pre>6057</pre>|<pre>2514</pre>|
