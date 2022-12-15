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
| `lanjian/day_14 input-lanjian` | 3.5 ± 0.1 | 3.4 | 5.5 | 3.64 ± 0.36 |
| `lanjian/day_14 input-mattcl` | 5.5 ± 0.4 | 5.2 | 10.4 | 5.59 ± 0.65 |
| `lanjian/day_14 input-pting` | 5.2 ± 0.2 | 5.0 | 6.7 | 5.36 ± 0.52 |
| `mattcl-solver/aoc run 14 input-lanjian` | 1.0 ± 0.1 | 0.9 | 2.7 | 1.04 ± 0.13 |
| `mattcl-solver/aoc run 14 input-mattcl` | 1.1 ± 0.1 | 0.9 | 1.7 | 1.09 ± 0.12 |
| `mattcl-solver/aoc run 14 input-pting` | 1.0 ± 0.1 | 0.8 | 3.6 | 1.00 |
| `python pting/day14/day14.py input-lanjian` | 1311.5 ± 25.6 | 1288.7 | 1380.8 | 1344.03 ± 127.35 |
| `python pting/day14/day14.py input-mattcl` | 1415.0 ± 7.3 | 1406.0 | 1432.2 | 1450.16 ± 134.68 |
| `python pting/day14/day14.py input-pting` | 1461.0 ± 7.0 | 1452.6 | 1469.2 | 1497.28 ± 139.02 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>715</pre>|<pre>25248</pre>|
|input-mattcl|<pre>1001</pre>|<pre>27976</pre>|
|input-pting|<pre>737</pre>|<pre>28145</pre>|
