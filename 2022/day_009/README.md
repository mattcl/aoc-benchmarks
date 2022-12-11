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
| `lanjian/day_09 input-lanjian` | 1.9 ± 0.1 | 1.7 | 3.6 | 1.31 ± 0.13 |
| `lanjian/day_09 input-mattcl` | 1.9 ± 0.2 | 1.7 | 4.0 | 1.35 ± 0.16 |
| `lanjian/day_09 input-pting` | 1.9 ± 0.1 | 1.8 | 4.1 | 1.36 ± 0.14 |
| `mattcl-solver/aoc run 9 input-lanjian` | 1.4 ± 0.1 | 1.3 | 3.3 | 1.00 |
| `mattcl-solver/aoc run 9 input-mattcl` | 1.4 ± 0.1 | 1.3 | 2.4 | 1.01 ± 0.10 |
| `mattcl-solver/aoc run 9 input-pting` | 1.5 ± 0.1 | 1.3 | 3.4 | 1.02 ± 0.11 |
| `python pting/day09/day09.py input-lanjian` | 74.1 ± 2.2 | 72.3 | 82.1 | 52.14 ± 4.68 |
| `python pting/day09/day09.py input-mattcl` | 75.9 ± 2.7 | 73.9 | 90.6 | 53.40 ± 4.91 |
| `python pting/day09/day09.py input-pting` | 76.1 ± 2.6 | 73.8 | 88.0 | 53.56 ± 4.91 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>5907</pre>|<pre>2303</pre>|
|input-mattcl|<pre>6057</pre>|<pre>2514</pre>|
|input-pting|<pre>6057</pre>|<pre>2514</pre>|
