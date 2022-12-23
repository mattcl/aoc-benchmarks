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
| `lanjian/day_21 input-lanjian` | 1.4 ± 0.1 | 1.3 | 3.4 | 1.27 ± 0.14 |
| `lanjian/day_21 input-mattcl` | 1.4 ± 0.1 | 1.3 | 2.3 | 1.25 ± 0.12 |
| `lanjian/day_21 input-pting` | 1.4 ± 0.2 | 1.2 | 4.4 | 1.24 ± 0.21 |
| `mattcl-solver/aoc run 21 input-lanjian` | 1.1 ± 0.1 | 1.0 | 1.8 | 1.00 |
| `mattcl-solver/aoc run 21 input-mattcl` | 1.1 ± 0.1 | 1.0 | 2.4 | 1.02 ± 0.10 |
| `mattcl-solver/aoc run 21 input-pting` | 1.1 ± 0.1 | 1.0 | 1.6 | 1.00 ± 0.10 |
| `python pting/day21/day21.py input-lanjian` | 441.6 ± 5.9 | 434.3 | 448.0 | 400.58 ± 28.52 |
| `python pting/day21/day21.py input-mattcl` | 440.6 ± 3.5 | 437.6 | 446.9 | 399.65 ± 28.13 |
| `python pting/day21/day21.py input-pting` | 441.2 ± 5.3 | 435.0 | 448.6 | 400.25 ± 28.40 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>43699799094202</pre>|<pre>3375719472770</pre>|
|input-mattcl|<pre>49288254556480</pre>|<pre>3558714869436</pre>|
|input-pting|<pre>85616733059734</pre>|<pre>3560324848168</pre>|
