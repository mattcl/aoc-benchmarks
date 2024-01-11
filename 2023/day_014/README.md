# Day 14 benchmarks

[link to problem](https://adventofcode.com/2023/day/14)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 14)

- [kcen](https://github.com/kcen/aoc2023) (python)
- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-lanjian | 3.1 ± 0.4 | 2.3 | 5.9 | 1.00 |
| mattcl | input-pting | 3.2 ± 2.6 | 2.0 | 40.1 | 1.02 ± 0.86 |
| mattcl | input-kcen | 3.5 ± 0.4 | 2.8 | 6.3 | 1.13 ± 0.18 |
| mattcl | input-mattcl | 4.1 ± 0.5 | 3.2 | 6.9 | 1.31 ± 0.22 |
| lanjian | input-pting | 19.0 ± 0.6 | 18.1 | 21.9 | 6.09 ± 0.74 |
| lanjian | input-lanjian | 20.1 ± 0.8 | 19.0 | 23.8 | 6.45 ± 0.80 |
| lanjian | input-kcen | 22.4 ± 0.6 | 21.5 | 26.4 | 7.20 ± 0.87 |
| lanjian | input-mattcl | 24.7 ± 0.8 | 23.5 | 28.1 | 7.93 ± 0.97 |
| mattcl-py | input-pting | 156.9 ± 2.2 | 153.0 | 160.6 | 50.36 ± 5.94 |
| mattcl-py | input-lanjian | 169.1 ± 1.7 | 166.6 | 173.2 | 54.28 ± 6.39 |
| pting | input-pting | 178.0 ± 4.0 | 171.0 | 184.5 | 57.15 ± 6.82 |
| pting | input-lanjian | 194.7 ± 4.2 | 185.2 | 201.4 | 62.48 ± 7.45 |
| mattcl-py | input-kcen | 196.2 ± 1.2 | 194.3 | 198.0 | 62.97 ± 7.39 |
| mattcl-py | input-mattcl | 204.1 ± 1.2 | 202.5 | 206.2 | 65.49 ± 7.68 |
| pting | input-kcen | 224.4 ± 4.1 | 217.5 | 232.0 | 72.03 ± 8.54 |
| pting | input-mattcl | 238.1 ± 4.3 | 231.2 | 246.4 | 76.40 ± 9.06 |
| kcen | input-pting | 596.5 ± 5.9 | 590.4 | 605.7 | 191.44 ± 22.51 |
| kcen | input-lanjian | 660.6 ± 11.9 | 645.9 | 672.4 | 212.04 ± 25.14 |
| kcen | input-kcen | 765.3 ± 2.3 | 762.7 | 766.8 | 245.63 ± 28.79 |
| kcen | input-mattcl | 840.2 ± 8.5 | 831.0 | 847.8 | 269.67 ± 31.72 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>108144</pre>|<pre>108404</pre>|
|input-lanjian|<pre>108935</pre>|<pre>100876</pre>|
|input-mattcl|<pre>105982</pre>|<pre>85175</pre>|
|input-pting|<pre>109596</pre>|<pre>96105</pre>|