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
| `lanjian/day_14 input-lanjian` | 3.6 ± 0.1 | 3.4 | 4.9 | 3.62 ± 0.35 |
| `lanjian/day_14 input-mattcl` | 5.5 ± 0.2 | 5.3 | 6.7 | 5.54 ± 0.52 |
| `lanjian/day_14 input-pting` | 5.2 ± 0.2 | 5.1 | 7.7 | 5.32 ± 0.51 |
| `mattcl-solver/aoc run 14 input-lanjian` | 1.0 ± 0.1 | 0.9 | 1.5 | 1.02 ± 0.11 |
| `mattcl-solver/aoc run 14 input-mattcl` | 1.1 ± 0.1 | 0.9 | 3.2 | 1.10 ± 0.14 |
| `mattcl-solver/aoc run 14 input-pting` | 1.0 ± 0.1 | 0.9 | 2.9 | 1.00 |
| `python pting/day14/day14.py input-lanjian` | 1301.2 ± 5.0 | 1291.6 | 1311.6 | 1319.46 ± 117.66 |
| `python pting/day14/day14.py input-mattcl` | 1419.7 ± 3.6 | 1415.5 | 1427.2 | 1439.70 ± 128.31 |
| `python pting/day14/day14.py input-pting` | 1482.4 ± 47.2 | 1460.1 | 1616.0 | 1503.24 ± 142.22 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>715</pre>|<pre>25248</pre>|
|input-mattcl|<pre>1001</pre>|<pre>27976</pre>|
|input-pting|<pre>737</pre>|<pre>28145</pre>|
