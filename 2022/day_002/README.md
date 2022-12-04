# Day 2 benchmarks

[link to problem](http://adventofcode.com/2022/day/2)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

[ci pipeline](http://ci.papercode.net:8080/teams/aoc2022/pipelines/aoc-compare-2022)

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Repos (with solutions for day 2)


- [aspidites](https://github.com/aspidites/aoc2022)
- [kcen](https://github.com/kcen/AdventOfCode)
- [lanjian](https://github.com/LanJian/aoc-2022)
- [mattcl](https://github.com/mattcl/aoc2022)
- [pting](https://github.com/pting/aoc2022)

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `aspidites-solver/aoc -i input-aspidites -d 2` | 12.1 ± 1.2 | 11.2 | 21.5 | 10.85 ± 4.23 |
| `aspidites-solver/aoc -i input-kcen -d 2` | 11.8 ± 0.6 | 11.2 | 15.4 | 10.51 ± 4.01 |
| `aspidites-solver/aoc -i input-lanjian -d 2` | 11.9 ± 0.5 | 11.4 | 16.2 | 10.69 ± 4.07 |
| `aspidites-solver/aoc -i input-mattcl -d 2` | 12.0 ± 0.7 | 11.2 | 15.6 | 10.77 ± 4.12 |
| `aspidites-solver/aoc -i input-pting -d 2` | 12.1 ± 1.9 | 11.0 | 29.6 | 10.78 ± 4.40 |
| `kcen/2022/02/solve input-aspidites` | 1.1 ± 0.6 | 0.6 | 15.8 | 1.01 ± 0.67 |
| `kcen/2022/02/solve input-kcen` | 1.3 ± 0.4 | 0.6 | 4.0 | 1.18 ± 0.58 |
| `kcen/2022/02/solve input-lanjian` | 1.2 ± 0.5 | 0.5 | 6.7 | 1.09 ± 0.64 |
| `kcen/2022/02/solve input-mattcl` | 1.3 ± 0.7 | 0.6 | 8.4 | 1.19 ± 0.79 |
| `kcen/2022/02/solve input-pting` | 1.3 ± 0.5 | 0.6 | 5.5 | 1.16 ± 0.62 |
| `lanjian/day_02 input-aspidites` | 1.7 ± 0.6 | 0.9 | 6.0 | 1.48 ± 0.77 |
| `lanjian/day_02 input-kcen` | 1.7 ± 0.6 | 0.9 | 10.4 | 1.55 ± 0.80 |
| `lanjian/day_02 input-lanjian` | 2.0 ± 1.1 | 1.0 | 13.5 | 1.81 ± 1.19 |
| `lanjian/day_02 input-mattcl` | 1.5 ± 0.5 | 0.7 | 4.5 | 1.31 ± 0.64 |
| `lanjian/day_02 input-pting` | 1.7 ± 0.5 | 1.0 | 5.3 | 1.50 ± 0.70 |
| `mattcl-solver/aoc run 2 input-aspidites` | 1.1 ± 0.4 | 0.6 | 4.6 | 1.00 |
| `mattcl-solver/aoc run 2 input-kcen` | 1.4 ± 0.5 | 0.7 | 5.8 | 1.30 ± 0.64 |
| `mattcl-solver/aoc run 2 input-lanjian` | 1.7 ± 0.8 | 0.7 | 11.7 | 1.53 ± 0.95 |
| `mattcl-solver/aoc run 2 input-mattcl` | 1.2 ± 0.4 | 0.7 | 3.8 | 1.07 ± 0.53 |
| `mattcl-solver/aoc run 2 input-pting` | 1.5 ± 0.8 | 0.7 | 13.3 | 1.31 ± 0.90 |
| `python pting/day02.py input-aspidites` | 33.1 ± 3.3 | 28.6 | 48.6 | 29.56 ± 11.58 |
| `python pting/day02.py input-kcen` | 34.3 ± 3.0 | 30.4 | 47.6 | 30.67 ± 11.91 |
| `python pting/day02.py input-lanjian` | 37.3 ± 4.9 | 30.8 | 55.5 | 33.33 ± 13.35 |
| `python pting/day02.py input-mattcl` | 35.2 ± 4.7 | 29.8 | 46.7 | 31.43 ± 12.61 |
| `python pting/day02.py input-pting` | 34.5 ± 3.4 | 29.5 | 44.0 | 30.80 ± 12.05 |
\n## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>10595</pre>|<pre>9541</pre>|
|input-mattcl|<pre>10404</pre>|<pre>10334</pre>|
|input-aspidites|<pre>14827</pre>|<pre>13889</pre>|
|input-pting|<pre>12458</pre>|<pre>12683</pre>|
|input-kcen|<pre>12855</pre>|<pre>13726</pre>|
