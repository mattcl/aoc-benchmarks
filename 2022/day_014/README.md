# Day 14 benchmarks

[link to problem](http://adventofcode.com/2022/day/14)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

[ci pipeline](http://ci.papercode.net:8080/teams/aoc2022/pipelines/aoc-compare-2022)

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "challenge" inputs (if any) were sourced from various places, including the subreddit.

## Repos (with solutions for day 14)


- [lanjian](https://github.com/LanJian/aoc-2022)
- [mattcl](https://github.com/mattcl/aoc2022)
- [pting](https://github.com/pting/aoc2022)

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `lanjian/day_14 input-lanjian` | 3.5 ± 0.2 | 3.3 | 7.0 | 3.67 ± 0.37 |
| `lanjian/day_14 input-mattcl` | 5.4 ± 0.2 | 5.2 | 7.3 | 5.64 ± 0.53 |
| `lanjian/day_14 input-pting` | 5.2 ± 0.2 | 5.0 | 6.9 | 5.42 ± 0.52 |
| `mattcl-solver/aoc run 14 input-lanjian` | 1.0 ± 0.1 | 0.9 | 3.0 | 1.04 ± 0.13 |
| `mattcl-solver/aoc run 14 input-mattcl` | 1.0 ± 0.1 | 0.9 | 2.8 | 1.09 ± 0.13 |
| `mattcl-solver/aoc run 14 input-pting` | 1.0 ± 0.1 | 0.8 | 2.8 | 1.00 |
| `python pting/day14/day14.py input-lanjian` | 162.6 ± 1.2 | 160.3 | 165.7 | 169.58 ± 14.92 |
| `python pting/day14/day14.py input-mattcl` | 166.2 ± 1.5 | 163.4 | 169.1 | 173.27 ± 15.28 |
| `python pting/day14/day14.py input-pting` | 163.6 ± 2.1 | 161.0 | 169.8 | 170.56 ± 15.11 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>715</pre>|<pre>25248</pre>|
|input-mattcl|<pre>1001</pre>|<pre>27976</pre>|
|input-pting|<pre>737</pre>|<pre>28145</pre>|
