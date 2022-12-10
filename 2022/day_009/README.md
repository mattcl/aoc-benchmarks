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
| `lanjian/day_09 input-lanjian` | 4.7 ± 1.0 | 3.0 | 9.1 | 1.09 ± 0.40 |
| `lanjian/day_09 input-mattcl` | 5.0 ± 1.7 | 3.3 | 24.6 | 1.15 ± 0.52 |
| `lanjian/day_09 input-pting` | 5.0 ± 1.4 | 2.9 | 15.9 | 1.15 ± 0.48 |
| `mattcl-solver/aoc run 9 input-lanjian` | 4.4 ± 1.5 | 2.3 | 14.2 | 1.02 ± 0.46 |
| `mattcl-solver/aoc run 9 input-mattcl` | 4.4 ± 1.2 | 2.2 | 11.0 | 1.01 ± 0.42 |
| `mattcl-solver/aoc run 9 input-pting` | 4.3 ± 1.3 | 2.2 | 16.1 | 1.00 |
| `python pting/day09.py input-lanjian` | 159.4 ± 13.6 | 140.3 | 182.8 | 36.86 ± 11.71 |
| `python pting/day09.py input-mattcl` | 171.2 ± 21.1 | 140.1 | 211.7 | 39.58 ± 13.07 |
| `python pting/day09.py input-pting` | 160.4 ± 16.7 | 140.0 | 202.2 | 37.08 ± 11.99 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>5907</pre>|<pre>2303</pre>|
|input-mattcl|<pre>6057</pre>|<pre>2514</pre>|
|input-pting|<pre>6057</pre>|<pre>2514</pre>|
