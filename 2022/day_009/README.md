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
| `lanjian/day_09 input-lanjian` | 1.9 ± 0.1 | 1.7 | 4.4 | 1.31 ± 0.10 |
| `lanjian/day_09 input-mattcl` | 1.9 ± 0.1 | 1.8 | 5.8 | 1.33 ± 0.12 |
| `lanjian/day_09 input-pting` | 1.9 ± 0.2 | 1.8 | 6.5 | 1.33 ± 0.12 |
| `mattcl-solver/aoc run 9 input-lanjian` | 1.4 ± 0.1 | 1.3 | 2.1 | 1.00 |
| `mattcl-solver/aoc run 9 input-mattcl` | 1.5 ± 0.2 | 1.4 | 6.2 | 1.03 ± 0.14 |
| `mattcl-solver/aoc run 9 input-pting` | 1.5 ± 0.1 | 1.4 | 1.9 | 1.01 ± 0.07 |
| `python pting/day09/day09.py input-lanjian` | 74.6 ± 2.0 | 72.7 | 81.7 | 51.70 ± 2.82 |
| `python pting/day09/day09.py input-mattcl` | 75.9 ± 2.8 | 73.7 | 86.6 | 52.65 ± 3.16 |
| `python pting/day09/day09.py input-pting` | 76.2 ± 2.4 | 73.7 | 86.3 | 52.83 ± 3.01 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>5907</pre>|<pre>2303</pre>|
|input-mattcl|<pre>6057</pre>|<pre>2514</pre>|
|input-pting|<pre>6057</pre>|<pre>2514</pre>|
