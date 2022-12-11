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
| `lanjian/day_09 input-lanjian` | 1.9 ± 0.1 | 1.7 | 3.6 | 1.30 ± 0.10 |
| `lanjian/day_09 input-mattcl` | 1.9 ± 0.1 | 1.7 | 3.8 | 1.33 ± 0.11 |
| `lanjian/day_09 input-pting` | 1.9 ± 0.1 | 1.7 | 3.8 | 1.34 ± 0.11 |
| `mattcl-solver/aoc run 9 input-lanjian` | 1.4 ± 0.1 | 1.3 | 3.2 | 1.00 |
| `mattcl-solver/aoc run 9 input-mattcl` | 1.5 ± 0.1 | 1.3 | 3.5 | 1.02 ± 0.09 |
| `mattcl-solver/aoc run 9 input-pting` | 1.5 ± 0.1 | 1.3 | 3.5 | 1.02 ± 0.09 |
| `python pting/day09/day09.py input-lanjian` | 73.6 ± 0.7 | 72.4 | 75.1 | 51.15 ± 3.12 |
| `python pting/day09/day09.py input-mattcl` | 75.9 ± 2.7 | 73.8 | 86.4 | 52.73 ± 3.68 |
| `python pting/day09/day09.py input-pting` | 75.8 ± 2.1 | 73.9 | 85.6 | 52.68 ± 3.50 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>5907</pre>|<pre>2303</pre>|
|input-mattcl|<pre>6057</pre>|<pre>2514</pre>|
|input-pting|<pre>6057</pre>|<pre>2514</pre>|
