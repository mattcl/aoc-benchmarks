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
| `lanjian/day_09 input-lanjian` | 5.0 ± 1.1 | 2.8 | 11.6 | 1.21 ± 0.41 |
| `lanjian/day_09 input-mattcl` | 5.2 ± 1.5 | 2.5 | 23.6 | 1.28 ± 0.49 |
| `lanjian/day_09 input-pting` | 8.5 ± 5.8 | 3.5 | 36.0 | 2.09 ± 1.52 |
| `mattcl-solver/aoc run 9 input-lanjian` | 4.2 ± 1.1 | 2.2 | 12.1 | 1.04 ± 0.37 |
| `mattcl-solver/aoc run 9 input-mattcl` | 4.1 ± 1.0 | 2.1 | 9.4 | 1.00 |
| `mattcl-solver/aoc run 9 input-pting` | 5.2 ± 3.4 | 2.2 | 41.8 | 1.27 ± 0.89 |
| `python pting/day09.py input-lanjian` | 140.2 ± 11.0 | 122.7 | 156.6 | 34.41 ± 9.23 |
| `python pting/day09.py input-mattcl` | 144.3 ± 11.3 | 132.3 | 176.5 | 35.41 ± 9.50 |
| `python pting/day09.py input-pting` | 156.6 ± 12.8 | 137.5 | 184.3 | 38.42 ± 10.35 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>5907</pre>|<pre>2303</pre>|
|input-mattcl|<pre>6057</pre>|<pre>2514</pre>|
|input-pting|<pre>6057</pre>|<pre>2514</pre>|
