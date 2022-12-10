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
| `lanjian/day_09 input-lanjian` | 5.2 ± 1.3 | 3.4 | 20.9 | 1.26 ± 0.46 |
| `lanjian/day_09 input-mattcl` | 5.1 ± 1.1 | 3.1 | 10.2 | 1.23 ± 0.41 |
| `lanjian/day_09 input-pting` | 5.8 ± 1.9 | 3.4 | 15.2 | 1.39 ± 0.58 |
| `mattcl-solver/aoc run 9 input-lanjian` | 4.5 ± 0.9 | 2.9 | 9.1 | 1.07 ± 0.35 |
| `mattcl-solver/aoc run 9 input-mattcl` | 4.1 ± 1.1 | 2.6 | 10.4 | 1.00 |
| `mattcl-solver/aoc run 9 input-pting` | 4.7 ± 1.5 | 3.0 | 17.0 | 1.13 ± 0.46 |
| `python pting/day09.py input-lanjian` | 169.1 ± 18.3 | 143.1 | 222.1 | 40.76 ± 11.44 |
| `python pting/day09.py input-mattcl` | 170.8 ± 18.3 | 146.6 | 207.2 | 41.17 ± 11.53 |
| `python pting/day09.py input-pting` | 152.4 ± 10.9 | 136.8 | 172.3 | 36.75 ± 9.87 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>5907</pre>|<pre>2303</pre>|
|input-mattcl|<pre>6057</pre>|<pre>2514</pre>|
|input-pting|<pre>6057</pre>|<pre>2514</pre>|
