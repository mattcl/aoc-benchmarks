# Day 22 benchmarks

[link to problem](http://adventofcode.com/2022/day/22)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

[ci pipeline](http://ci.papercode.net:8080/teams/aoc2022/pipelines/aoc-compare-2022)

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "challenge" inputs (if any) were sourced from various places, including the subreddit.

## Repos (with solutions for day 22)


- [lanjian](https://github.com/LanJian/aoc-2022)
- [mattcl](https://github.com/mattcl/aoc2022)
- [pting](https://github.com/pting/aoc2022)

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `lanjian/day_22 input-lanjian` | 1.4 ± 0.1 | 1.2 | 3.1 | 1.22 ± 0.11 |
| `lanjian/day_22 input-mattcl` | 1.4 ± 0.1 | 1.2 | 3.2 | 1.21 ± 0.13 |
| `lanjian/day_22 input-pting` | 1.4 ± 0.1 | 1.2 | 1.9 | 1.21 ± 0.10 |
| `mattcl-solver/aoc run 22 input-lanjian` | 1.1 ± 0.1 | 1.0 | 2.9 | 1.00 |
| `mattcl-solver/aoc run 22 input-mattcl` | 1.1 ± 0.1 | 1.0 | 3.3 | 1.01 ± 0.10 |
| `mattcl-solver/aoc run 22 input-pting` | 1.1 ± 0.1 | 1.0 | 2.9 | 1.01 ± 0.09 |
| `python pting/day22/day22.py input-lanjian` | 91.7 ± 1.4 | 90.2 | 96.9 | 82.18 ± 5.42 |
| `python pting/day22/day22.py input-mattcl` | 90.4 ± 1.3 | 88.9 | 95.4 | 80.94 ± 5.33 |
| `python pting/day22/day22.py input-pting` | 89.9 ± 1.4 | 88.1 | 93.8 | 80.50 ± 5.32 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>30552</pre>|<pre>184106</pre>|
|input-mattcl|<pre>75254</pre>|<pre>108311</pre>|
|input-pting|<pre>123046</pre>|<pre>195032</pre>|
