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
| `lanjian/day_15 input-lanjian` | 0.6 ± 0.2 | 0.5 | 6.7 | 1.02 ± 0.27 |
| `lanjian/day_15 input-mattcl` | 0.7 ± 0.2 | 0.5 | 4.2 | 1.11 ± 0.27 |
| `lanjian/day_15 input-pting` | 0.6 ± 0.1 | 0.5 | 1.4 | 1.00 |
| `mattcl-solver/aoc run 15 input-lanjian` | 0.9 ± 0.1 | 0.7 | 3.8 | 1.39 ± 0.19 |
| `mattcl-solver/aoc run 15 input-mattcl` | 0.9 ± 0.1 | 0.8 | 1.5 | 1.45 ± 0.17 |
| `mattcl-solver/aoc run 15 input-pting` | 0.9 ± 0.2 | 0.8 | 4.0 | 1.49 ± 0.28 |
| `python pting/day15/day15.py input-lanjian` | 17804.9 ± 514.2 | 17212.3 | 18133.3 | 28441.40 ± 2786.24 |
| `python pting/day15/day15.py input-mattcl` | 31294.6 ± 1786.0 | 29770.1 | 33259.7 | 49989.82 ± 5480.73 |
| `python pting/day15/day15.py input-pting` | 27256.2 ± 799.3 | 26425.5 | 28020.0 | 43538.80 ± 4271.03 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>4582667</pre>|<pre>10961118625406</pre>|
|input-mattcl|<pre>4873353</pre>|<pre>11600823139120</pre>|
|input-pting|<pre>4748135</pre>|<pre>13743542639657</pre>|
