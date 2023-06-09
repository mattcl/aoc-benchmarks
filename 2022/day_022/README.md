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
| `lanjian/day_22 input-lanjian` | 1.7 ± 0.1 | 1.5 | 2.6 | 1.23 ± 0.12 |
| `lanjian/day_22 input-mattcl` | 1.6 ± 0.1 | 1.5 | 2.2 | 1.23 ± 0.12 |
| `lanjian/day_22 input-pting` | 1.7 ± 0.2 | 1.5 | 4.4 | 1.28 ± 0.15 |
| `mattcl-solver/aoc run 22 input-lanjian` | 1.3 ± 0.1 | 1.2 | 3.8 | 1.00 ± 0.11 |
| `mattcl-solver/aoc run 22 input-mattcl` | 1.3 ± 0.1 | 1.2 | 2.1 | 1.00 |
| `mattcl-solver/aoc run 22 input-pting` | 1.3 ± 0.1 | 1.2 | 1.9 | 1.00 ± 0.10 |
| `python pting/day22/day22.py input-lanjian` | 112.9 ± 1.8 | 111.9 | 121.1 | 84.03 ± 6.16 |
| `python pting/day22/day22.py input-mattcl` | 111.8 ± 0.6 | 111.2 | 113.4 | 83.19 ± 5.97 |
| `python pting/day22/day22.py input-pting` | 110.8 ± 0.4 | 110.2 | 111.8 | 82.46 ± 5.91 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>30552</pre>|<pre>184106</pre>|
|input-mattcl|<pre>75254</pre>|<pre>108311</pre>|
|input-pting|<pre>123046</pre>|<pre>195032</pre>|
