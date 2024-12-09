# Day 3 benchmarks

[link to problem](https://adventofcode.com/2024/day/3)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2024)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 3)

- [kcen](https://github.com/kcen/aoc2024) (nim)
- [lanjian](https://github.com/lanjian/aoc-2024) (rust)
- [mattcl](https://github.com/mattcl/aoc2024) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2024-py) (python)
- [mikofo](https://github.com/mikofo/aoc2024) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.2 | 1.9 | 1.00 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.3 | 1.8 | 1.00 ± 0.23 |
| mattcl | input-kcen | 1.1 ± 0.2 | 0.5 | 1.9 | 1.01 ± 0.25 |
| mattcl | input-mikofo | 1.2 ± 0.2 | 0.1 | 2.0 | 1.03 ± 0.27 |
| kcen | input-mattcl | 1.3 ± 0.2 | 0.6 | 2.2 | 1.17 ± 0.28 |
| kcen | input-kcen | 1.3 ± 0.2 | 0.7 | 2.0 | 1.17 ± 0.26 |
| kcen | input-mikofo | 1.3 ± 0.2 | 0.6 | 1.9 | 1.19 ± 0.24 |
| kcen | input-lanjian | 1.4 ± 0.2 | 0.7 | 2.1 | 1.21 ± 0.27 |
| lanjian | input-kcen | 1.9 ± 0.3 | 1.1 | 2.6 | 1.66 ± 0.40 |
| lanjian | input-mikofo | 1.9 ± 0.4 | 1.3 | 3.0 | 1.70 ± 0.41 |
| lanjian | input-lanjian | 1.9 ± 0.4 | 1.2 | 3.4 | 1.71 ± 0.42 |
| lanjian | input-mattcl | 1.9 ± 0.4 | 1.1 | 3.1 | 1.73 ± 0.43 |
| mattcl-py | input-mikofo | 16.8 ± 0.6 | 15.6 | 19.6 | 15.00 ± 2.44 |
| mattcl-py | input-lanjian | 17.0 ± 0.6 | 16.0 | 19.7 | 15.12 ± 2.47 |
| mattcl-py | input-kcen | 17.0 ± 0.6 | 15.9 | 19.8 | 15.15 ± 2.47 |
| mattcl-py | input-mattcl | 17.0 ± 0.6 | 15.6 | 20.4 | 15.16 ± 2.48 |
| mikofo | input-lanjian | 19.7 ± 0.7 | 18.6 | 22.7 | 17.57 ± 2.86 |
| mikofo | input-mikofo | 19.7 ± 0.6 | 18.6 | 22.3 | 17.57 ± 2.85 |
| mikofo | input-mattcl | 19.7 ± 0.7 | 18.4 | 22.9 | 17.58 ± 2.87 |
| mikofo | input-kcen | 19.7 ± 0.7 | 18.6 | 22.8 | 17.60 ± 2.87 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>165225049</pre>|<pre>108830766</pre>|
|input-lanjian|<pre>182619815</pre>|<pre>80747545</pre>|
|input-mattcl|<pre>170068701</pre>|<pre>78683433</pre>|
|input-mikofo|<pre>189527826</pre>|<pre>63013756</pre>|