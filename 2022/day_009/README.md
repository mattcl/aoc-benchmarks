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
| `lanjian/day_09 input-lanjian` | 5.1 ± 1.5 | 3.1 | 14.7 | 1.29 ± 0.55 |
| `lanjian/day_09 input-mattcl` | 5.4 ± 1.5 | 3.1 | 17.1 | 1.34 ± 0.58 |
| `lanjian/day_09 input-pting` | 5.4 ± 1.2 | 3.3 | 12.9 | 1.35 ± 0.53 |
| `mattcl-solver/aoc run 9 input-lanjian` | 4.0 ± 1.3 | 2.2 | 14.3 | 1.00 |
| `mattcl-solver/aoc run 9 input-mattcl` | 4.2 ± 1.1 | 2.4 | 12.9 | 1.05 ± 0.44 |
| `mattcl-solver/aoc run 9 input-pting` | 4.3 ± 1.2 | 2.5 | 12.8 | 1.09 ± 0.46 |
| `python pting/day09.py input-lanjian` | 164.9 ± 20.1 | 139.0 | 207.8 | 41.21 ± 14.28 |
| `python pting/day09.py input-mattcl` | 176.7 ± 21.6 | 146.5 | 206.5 | 44.17 ± 15.31 |
| `python pting/day09.py input-pting` | 175.3 ± 16.0 | 147.7 | 203.0 | 43.80 ± 14.76 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>5907</pre>|<pre>2303</pre>|
|input-mattcl|<pre>6057</pre>|<pre>2514</pre>|
|input-pting|<pre>6057</pre>|<pre>2514</pre>|
