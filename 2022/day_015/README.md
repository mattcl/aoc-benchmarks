# Day 15 benchmarks

[link to problem](http://adventofcode.com/2022/day/15)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

[ci pipeline](http://ci.papercode.net:8080/teams/aoc2022/pipelines/aoc-compare-2022)

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "challenge" inputs (if any) were sourced from various places, including the subreddit.

## Repos (with solutions for day 15)


- [lanjian](https://github.com/LanJian/aoc-2022)
- [mattcl](https://github.com/mattcl/aoc2022)
- [pting](https://github.com/pting/aoc2022)

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `lanjian/day_15 input-lanjian` | 0.6 ± 0.1 | 0.5 | 3.2 | 1.00 |
| `lanjian/day_15 input-mattcl` | 0.7 ± 0.1 | 0.5 | 3.2 | 1.16 ± 0.25 |
| `lanjian/day_15 input-pting` | 0.6 ± 0.1 | 0.5 | 1.1 | 1.04 ± 0.19 |
| `mattcl-solver/aoc run 15 input-lanjian` | 0.7 ± 0.1 | 0.6 | 2.6 | 1.24 ± 0.23 |
| `mattcl-solver/aoc run 15 input-mattcl` | 0.9 ± 0.1 | 0.7 | 1.2 | 1.45 ± 0.24 |
| `mattcl-solver/aoc run 15 input-pting` | 0.8 ± 0.1 | 0.7 | 2.3 | 1.32 ± 0.23 |
| `python pting/day15/day15.py input-lanjian` | 17971.8 ± 447.0 | 17462.3 | 18297.8 | 30495.64 ± 4576.57 |
| `python pting/day15/day15.py input-mattcl` | 31557.8 ± 816.7 | 30672.4 | 32281.6 | 53549.15 ± 8045.40 |
| `python pting/day15/day15.py input-pting` | 29042.8 ± 1207.6 | 27838.1 | 30253.2 | 49281.65 ± 7575.94 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>4582667</pre>|<pre>10961118625406</pre>|
|input-mattcl|<pre>4873353</pre>|<pre>11600823139120</pre>|
|input-pting|<pre>4748135</pre>|<pre>13743542639657</pre>|
