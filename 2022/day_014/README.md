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
| `lanjian/day_14 input-lanjian` | 3.6 ± 0.2 | 3.4 | 7.0 | 3.72 ± 0.32 |
| `lanjian/day_14 input-mattcl` | 5.4 ± 0.2 | 5.2 | 7.0 | 5.67 ± 0.43 |
| `lanjian/day_14 input-pting` | 5.3 ± 0.2 | 5.0 | 7.6 | 5.53 ± 0.44 |
| `mattcl-solver/aoc run 14 input-lanjian` | 1.0 ± 0.1 | 0.9 | 2.8 | 1.01 ± 0.11 |
| `mattcl-solver/aoc run 14 input-mattcl` | 1.0 ± 0.1 | 0.9 | 3.3 | 1.08 ± 0.11 |
| `mattcl-solver/aoc run 14 input-pting` | 1.0 ± 0.1 | 0.8 | 1.4 | 1.00 |
| `python pting/day14/day14.py input-lanjian` | 1301.6 ± 28.7 | 1285.7 | 1381.2 | 1360.96 ± 96.09 |
| `python pting/day14/day14.py input-mattcl` | 1408.4 ± 6.5 | 1399.1 | 1420.2 | 1472.67 ± 99.00 |
| `python pting/day14/day14.py input-pting` | 1454.4 ± 7.0 | 1441.5 | 1463.9 | 1520.75 ± 102.25 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>715</pre>|<pre>25248</pre>|
|input-mattcl|<pre>1001</pre>|<pre>27976</pre>|
|input-pting|<pre>737</pre>|<pre>28145</pre>|
