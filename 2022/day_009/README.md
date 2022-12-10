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
| `lanjian/day_09 input-lanjian` | 6.7 ± 2.9 | 3.5 | 31.7 | 1.56 ± 0.78 |
| `lanjian/day_09 input-mattcl` | 6.4 ± 2.2 | 3.6 | 22.2 | 1.49 ± 0.64 |
| `lanjian/day_09 input-pting` | 5.0 ± 1.2 | 2.8 | 12.4 | 1.16 ± 0.41 |
| `mattcl-solver/aoc run 9 input-lanjian` | 5.5 ± 3.3 | 2.8 | 44.8 | 1.29 ± 0.85 |
| `mattcl-solver/aoc run 9 input-mattcl` | 4.8 ± 1.5 | 2.8 | 23.3 | 1.11 ± 0.45 |
| `mattcl-solver/aoc run 9 input-pting` | 4.3 ± 1.1 | 2.5 | 12.6 | 1.00 |
| `python pting/day09.py input-lanjian` | 187.0 ± 22.5 | 154.0 | 242.7 | 43.67 ± 12.43 |
| `python pting/day09.py input-mattcl` | 167.6 ± 18.6 | 148.4 | 210.7 | 39.15 ± 10.99 |
| `python pting/day09.py input-pting` | 173.0 ± 19.9 | 147.7 | 209.1 | 40.40 ± 11.40 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>5907</pre>|<pre>2303</pre>|
|input-mattcl|<pre>6057</pre>|<pre>2514</pre>|
|input-pting|<pre>6057</pre>|<pre>2514</pre>|
