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
| `lanjian/day_09 input-kcen` | 2.0 ± 0.2 | 1.8 | 5.5 | 1.35 ± 0.16 |
| `lanjian/day_09 input-lanjian` | 1.9 ± 0.1 | 1.7 | 2.5 | 1.29 ± 0.12 |
| `lanjian/day_09 input-mattcl` | 1.9 ± 0.1 | 1.8 | 3.9 | 1.32 ± 0.13 |
| `lanjian/day_09 input-pting` | 2.0 ± 0.2 | 1.8 | 4.5 | 1.34 ± 0.19 |
| `mattcl-solver/aoc run 9 input-kcen` | 1.5 ± 0.4 | 1.4 | 8.1 | 1.04 ± 0.26 |
| `mattcl-solver/aoc run 9 input-lanjian` | 1.5 ± 0.1 | 1.3 | 3.5 | 1.00 |
| `mattcl-solver/aoc run 9 input-mattcl` | 1.5 ± 0.1 | 1.3 | 3.5 | 1.01 ± 0.11 |
| `mattcl-solver/aoc run 9 input-pting` | 1.5 ± 0.1 | 1.3 | 3.2 | 1.01 ± 0.10 |
| `python pting/day09/day09.py input-kcen` | 80.1 ± 3.8 | 76.0 | 89.7 | 55.11 ± 5.05 |
| `python pting/day09/day09.py input-lanjian` | 74.7 ± 2.2 | 72.3 | 83.8 | 51.40 ± 4.30 |
| `python pting/day09/day09.py input-mattcl` | 75.6 ± 2.0 | 73.9 | 81.9 | 52.02 ± 4.29 |
| `python pting/day09/day09.py input-pting` | 76.4 ± 2.6 | 74.0 | 85.0 | 52.56 ± 4.48 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>5907</pre>|<pre>2303</pre>|
|input-mattcl|<pre>6057</pre>|<pre>2514</pre>|
|input-pting|<pre>6057</pre>|<pre>2514</pre>|
|input-kcen|<pre>6470</pre>|<pre>2658</pre>|
