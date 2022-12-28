# Day 21 benchmarks

[link to problem](http://adventofcode.com/2022/day/21)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

[ci pipeline](http://ci.papercode.net:8080/teams/aoc2022/pipelines/aoc-compare-2022)

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "challenge" inputs (if any) were sourced from various places, including the subreddit.

## Repos (with solutions for day 21)


- [lanjian](https://github.com/LanJian/aoc-2022)
- [mattcl](https://github.com/mattcl/aoc2022)
- [pting](https://github.com/pting/aoc2022)

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `lanjian/day_21 input-lanjian` | 1.3 ± 0.1 | 1.2 | 3.3 | 1.19 ± 0.11 |
| `lanjian/day_21 input-mattcl` | 1.4 ± 0.1 | 1.2 | 3.3 | 1.23 ± 0.10 |
| `lanjian/day_21 input-pting` | 1.3 ± 0.1 | 1.2 | 3.2 | 1.19 ± 0.10 |
| `mattcl-solver/aoc run 21 input-lanjian` | 1.1 ± 0.1 | 1.0 | 1.6 | 1.00 |
| `mattcl-solver/aoc run 21 input-mattcl` | 1.1 ± 0.1 | 1.0 | 3.0 | 1.02 ± 0.09 |
| `mattcl-solver/aoc run 21 input-pting` | 1.1 ± 0.1 | 1.0 | 3.0 | 1.01 ± 0.09 |
| `python pting/day21/day21.py input-lanjian` | 435.9 ± 1.7 | 434.0 | 438.5 | 394.34 ± 22.85 |
| `python pting/day21/day21.py input-mattcl` | 434.1 ± 1.6 | 431.9 | 435.9 | 392.79 ± 22.76 |
| `python pting/day21/day21.py input-pting` | 431.5 ± 5.2 | 426.6 | 441.1 | 390.41 ± 23.06 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>43699799094202</pre>|<pre>3375719472770</pre>|
|input-mattcl|<pre>49288254556480</pre>|<pre>3558714869436</pre>|
|input-pting|<pre>85616733059734</pre>|<pre>3560324848168</pre>|
