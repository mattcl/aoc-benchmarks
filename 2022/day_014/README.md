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
| `lanjian/day_14 input-lanjian` | 3.5 ± 0.1 | 3.3 | 5.2 | 3.67 ± 0.39 |
| `lanjian/day_14 input-mattcl` | 5.4 ± 0.2 | 5.2 | 6.9 | 5.62 ± 0.61 |
| `lanjian/day_14 input-pting` | 5.2 ± 0.2 | 5.0 | 7.2 | 5.43 ± 0.58 |
| `mattcl-solver/aoc run 14 input-lanjian` | 1.0 ± 0.1 | 0.9 | 2.9 | 1.03 ± 0.14 |
| `mattcl-solver/aoc run 14 input-mattcl` | 1.0 ± 0.1 | 0.9 | 1.8 | 1.04 ± 0.13 |
| `mattcl-solver/aoc run 14 input-pting` | 1.0 ± 0.1 | 0.8 | 3.1 | 1.00 |
| `python pting/day14/day14.py input-lanjian` | 1322.8 ± 59.0 | 1289.8 | 1467.3 | 1370.72 ± 148.69 |
| `python pting/day14/day14.py input-mattcl` | 1417.0 ± 5.6 | 1405.4 | 1424.3 | 1468.30 ± 145.32 |
| `python pting/day14/day14.py input-pting` | 1465.4 ± 4.7 | 1455.9 | 1472.2 | 1518.47 ± 150.24 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>715</pre>|<pre>25248</pre>|
|input-mattcl|<pre>1001</pre>|<pre>27976</pre>|
|input-pting|<pre>737</pre>|<pre>28145</pre>|
