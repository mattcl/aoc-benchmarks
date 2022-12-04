# Day 1 benchmarks

[link to problem](http://adventofcode.com/2022/day/1)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

[ci pipeline](http://ci.papercode.net:8080/teams/aoc2022/pipelines/aoc-compare-2022)

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Repos (with solutions for day 1)


- [aspidites](https://github.com/aspidites/aoc2022)
- [kcen](https://github.com/kcen/AdventOfCode)
- [lanjian](https://github.com/LanJian/aoc-2022)
- [mattcl](https://github.com/mattcl/aoc2022)
- [pting](https://github.com/pting/aoc2022)

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `aspidites-solver/aoc -i input-aspidites -d 1` | 12.2 ± 1.5 | 11.2 | 25.1 | 13.00 ± 5.62 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 12.5 ± 0.9 | 11.5 | 18.0 | 13.34 ± 5.61 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 12.1 ± 0.8 | 11.3 | 16.5 | 12.98 ± 5.45 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 12.1 ± 0.7 | 11.3 | 16.3 | 12.91 ± 5.41 |
| `aspidites-solver/aoc -i input-pting -d 1` | 11.8 ± 0.5 | 11.2 | 14.3 | 12.67 ± 5.28 |
| `kcen/2022/01/solve input-aspidites` | 109.7 ± 8.8 | 95.4 | 127.3 | 117.37 ± 49.58 |
| `kcen/2022/01/solve input-kcen` | 111.5 ± 10.0 | 99.0 | 134.5 | 119.34 ± 50.63 |
| `kcen/2022/01/solve input-lanjian` | 108.1 ± 6.9 | 98.1 | 123.3 | 115.64 ± 48.52 |
| `kcen/2022/01/solve input-mattcl` | 110.9 ± 14.2 | 93.8 | 152.6 | 118.63 ± 51.47 |
| `kcen/2022/01/solve input-pting` | 101.9 ± 7.3 | 90.5 | 119.3 | 109.03 ± 45.87 |
| `lanjian/day_01 input-aspidites` | 1.2 ± 0.5 | 0.7 | 13.0 | 1.30 ± 0.78 |
| `lanjian/day_01 input-kcen` | 1.7 ± 0.6 | 0.8 | 7.6 | 1.85 ± 1.01 |
| `lanjian/day_01 input-lanjian` | 1.3 ± 0.5 | 0.6 | 7.3 | 1.42 ± 0.80 |
| `lanjian/day_01 input-mattcl` | 1.4 ± 0.7 | 0.6 | 7.4 | 1.51 ± 1.01 |
| `lanjian/day_01 input-pting` | 1.4 ± 0.5 | 0.7 | 6.3 | 1.46 ± 0.83 |
| `mattcl-solver/aoc run 1 input-aspidites` | 0.9 ± 0.4 | 0.4 | 4.4 | 1.00 |
| `mattcl-solver/aoc run 1 input-kcen` | 1.1 ± 0.5 | 0.4 | 4.2 | 1.14 ± 0.68 |
| `mattcl-solver/aoc run 1 input-lanjian` | 1.3 ± 0.5 | 0.5 | 4.8 | 1.36 ± 0.79 |
| `mattcl-solver/aoc run 1 input-mattcl` | 1.1 ± 0.4 | 0.5 | 4.6 | 1.14 ± 0.64 |
| `mattcl-solver/aoc run 1 input-pting` | 1.3 ± 0.8 | 0.5 | 10.2 | 1.44 ± 1.05 |
| `python pting/day01.py input-aspidites` | 32.6 ± 3.3 | 28.6 | 40.9 | 34.86 ± 14.88 |
| `python pting/day01.py input-kcen` | 36.3 ± 5.1 | 28.5 | 49.5 | 38.80 ± 16.99 |
| `python pting/day01.py input-lanjian` | 33.4 ± 3.1 | 28.6 | 44.8 | 35.76 ± 15.21 |
| `python pting/day01.py input-mattcl` | 36.3 ± 7.4 | 27.8 | 74.5 | 38.84 ± 17.96 |
| `python pting/day01.py input-pting` | 34.3 ± 3.6 | 29.0 | 45.5 | 36.71 ± 15.69 |
\n## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>69693</pre>|<pre>200945</pre>|
|input-mattcl|<pre>69795</pre>|<pre>208437</pre>|
|input-aspidites|<pre>70764</pre>|<pre>203905</pre>|
|input-pting|<pre>68802</pre>|<pre>205370</pre>|
|input-kcen|<pre>65912</pre>|<pre>195625</pre>|
