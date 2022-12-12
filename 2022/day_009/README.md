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
| `lanjian/day_09 input-kcen` | 2.0 ± 0.2 | 1.8 | 9.2 | 1.34 ± 0.18 |
| `lanjian/day_09 input-lanjian` | 1.9 ± 0.1 | 1.8 | 4.5 | 1.32 ± 0.12 |
| `lanjian/day_09 input-mattcl` | 2.0 ± 0.1 | 1.8 | 4.0 | 1.34 ± 0.13 |
| `lanjian/day_09 input-pting` | 2.0 ± 0.1 | 1.8 | 4.0 | 1.37 ± 0.12 |
| `mattcl-solver/aoc run 9 input-kcen` | 1.5 ± 0.2 | 1.4 | 10.7 | 1.03 ± 0.18 |
| `mattcl-solver/aoc run 9 input-lanjian` | 1.5 ± 0.1 | 1.3 | 3.7 | 1.00 |
| `mattcl-solver/aoc run 9 input-mattcl` | 1.5 ± 0.1 | 1.3 | 2.4 | 1.03 ± 0.10 |
| `mattcl-solver/aoc run 9 input-pting` | 1.5 ± 0.2 | 1.3 | 6.2 | 1.04 ± 0.12 |
| `python pting/day09/day09.py input-kcen` | 78.1 ± 2.6 | 76.1 | 89.8 | 53.60 ± 3.87 |
| `python pting/day09/day09.py input-lanjian` | 74.9 ± 2.9 | 72.4 | 85.2 | 51.41 ± 3.84 |
| `python pting/day09/day09.py input-mattcl` | 75.2 ± 1.9 | 73.5 | 84.6 | 51.60 ± 3.55 |
| `python pting/day09/day09.py input-pting` | 76.2 ± 3.3 | 73.5 | 88.2 | 52.26 ± 4.02 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>5907</pre>|<pre>2303</pre>|
|input-mattcl|<pre>6057</pre>|<pre>2514</pre>|
|input-pting|<pre>6057</pre>|<pre>2514</pre>|
|input-kcen|<pre>6470</pre>|<pre>2658</pre>|
