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
| `lanjian/day_14 input-lanjian` | 3.6 ± 0.3 | 3.4 | 9.8 | 3.72 ± 0.47 |
| `lanjian/day_14 input-mattcl` | 5.4 ± 0.2 | 5.2 | 7.1 | 5.68 ± 0.50 |
| `lanjian/day_14 input-pting` | 5.2 ± 0.2 | 5.0 | 7.1 | 5.47 ± 0.48 |
| `mattcl-solver/aoc run 14 input-lanjian` | 1.0 ± 0.1 | 0.9 | 3.2 | 1.00 |
| `mattcl-solver/aoc run 14 input-mattcl` | 1.1 ± 0.1 | 0.9 | 1.5 | 1.11 ± 0.11 |
| `mattcl-solver/aoc run 14 input-pting` | 1.0 ± 0.1 | 0.8 | 2.5 | 1.02 ± 0.12 |
| `python pting/day14/day14.py input-lanjian` | 1306.3 ± 20.2 | 1289.3 | 1361.8 | 1364.38 ± 112.42 |
| `python pting/day14/day14.py input-mattcl` | 1429.6 ± 40.0 | 1403.4 | 1541.5 | 1493.08 ± 127.86 |
| `python pting/day14/day14.py input-pting` | 1466.6 ± 8.3 | 1456.2 | 1480.1 | 1531.80 ± 124.26 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>715</pre>|<pre>25248</pre>|
|input-mattcl|<pre>1001</pre>|<pre>27976</pre>|
|input-pting|<pre>737</pre>|<pre>28145</pre>|
