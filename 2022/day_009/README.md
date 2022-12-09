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
| `lanjian/day_09 input-lanjian` | 13.6 ± 10.7 | 3.9 | 54.6 | 2.74 ± 2.42 |
| `lanjian/day_09 input-mattcl` | 5.9 ± 1.2 | 3.6 | 10.0 | 1.18 ± 0.53 |
| `lanjian/day_09 input-pting` | 6.1 ± 1.6 | 3.7 | 15.3 | 1.22 ± 0.58 |
| `mattcl-solver/aoc run 9 input-lanjian` | 5.0 ± 2.0 | 2.8 | 19.8 | 1.00 |
| `mattcl-solver/aoc run 9 input-mattcl` | 5.3 ± 1.9 | 3.1 | 26.4 | 1.07 ± 0.57 |
| `mattcl-solver/aoc run 9 input-pting` | 5.5 ± 1.7 | 2.6 | 15.9 | 1.11 ± 0.56 |
| `python pting/day09.py input-lanjian` | 164.4 ± 14.6 | 145.1 | 201.7 | 33.11 ± 13.52 |
| `python pting/day09.py input-mattcl` | 166.7 ± 12.5 | 152.8 | 194.8 | 33.56 ± 13.60 |
| `python pting/day09.py input-pting` | 156.0 ± 11.9 | 140.9 | 184.5 | 31.42 ± 12.75 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>5907</pre>|<pre>2303</pre>|
|input-mattcl|<pre>6057</pre>|<pre>2514</pre>|
|input-pting|<pre>6057</pre>|<pre>2514</pre>|
