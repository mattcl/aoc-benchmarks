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
| `lanjian/day_14 input-lanjian` | 12.0 ± 0.3 | 11.7 | 13.9 | 12.82 ± 1.33 |
| `lanjian/day_14 input-mattcl` | 13.1 ± 0.3 | 12.7 | 15.0 | 13.99 ± 1.45 |
| `lanjian/day_14 input-pting` | 13.6 ± 0.3 | 13.3 | 16.6 | 14.61 ± 1.53 |
| `mattcl-solver/aoc run 14 input-lanjian` | 1.0 ± 0.1 | 0.8 | 1.4 | 1.04 ± 0.13 |
| `mattcl-solver/aoc run 14 input-mattcl` | 1.0 ± 0.1 | 0.9 | 2.9 | 1.10 ± 0.14 |
| `mattcl-solver/aoc run 14 input-pting` | 0.9 ± 0.1 | 0.8 | 4.0 | 1.00 |
| `python pting/day14/day14.py input-lanjian` | 1315.6 ± 59.7 | 1290.2 | 1484.7 | 1408.67 ± 156.91 |
| `python pting/day14/day14.py input-mattcl` | 1414.8 ± 4.0 | 1409.7 | 1422.3 | 1514.84 ± 154.14 |
| `python pting/day14/day14.py input-pting` | 1478.3 ± 50.1 | 1451.6 | 1619.5 | 1582.88 ± 169.69 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>715</pre>|<pre>25248</pre>|
|input-mattcl|<pre>1001</pre>|<pre>27976</pre>|
|input-pting|<pre>737</pre>|<pre>28145</pre>|
