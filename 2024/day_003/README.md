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
| mattcl | input-kcen | 1.2 ± 0.3 | 0.2 | 2.1 | 1.00 |
| kcen | input-kcen | 1.3 ± 0.3 | 0.3 | 2.4 | 1.11 ± 0.42 |
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.5 | 2.0 | 1.13 ± 0.37 |
| mattcl | input-mikofo | 1.4 ± 0.2 | 0.6 | 2.1 | 1.13 ± 0.36 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 0.8 | 1.8 | 1.14 ± 0.34 |
| kcen | input-mattcl | 1.4 ± 0.2 | 0.4 | 2.3 | 1.21 ± 0.38 |
| kcen | input-mikofo | 1.5 ± 0.2 | 0.9 | 2.3 | 1.21 ± 0.38 |
| kcen | input-lanjian | 1.5 ± 0.3 | 0.5 | 2.9 | 1.24 ± 0.41 |
| lanjian | input-kcen | 2.0 ± 0.4 | 0.7 | 3.4 | 1.70 ± 0.57 |
| lanjian | input-mattcl | 2.0 ± 0.4 | 1.1 | 3.2 | 1.70 ± 0.58 |
| lanjian | input-mikofo | 2.0 ± 0.3 | 1.3 | 3.1 | 1.71 ± 0.55 |
| lanjian | input-lanjian | 2.1 ± 0.3 | 1.1 | 2.9 | 1.73 ± 0.56 |
| mattcl-py | input-mikofo | 17.1 ± 0.6 | 16.2 | 20.0 | 14.31 ± 4.02 |
| mattcl-py | input-lanjian | 17.2 ± 0.6 | 16.3 | 20.1 | 14.35 ± 4.03 |
| mattcl-py | input-mattcl | 17.3 ± 0.7 | 16.0 | 20.0 | 14.42 ± 4.06 |
| mattcl-py | input-kcen | 17.3 ± 0.9 | 16.1 | 20.5 | 14.46 ± 4.10 |
| mikofo | input-lanjian | 20.0 ± 0.6 | 18.9 | 22.8 | 16.65 ± 4.67 |
| mikofo | input-kcen | 20.0 ± 0.7 | 18.3 | 22.9 | 16.70 ± 4.69 |
| mikofo | input-mattcl | 20.1 ± 0.6 | 19.3 | 22.8 | 16.75 ± 4.70 |
| mikofo | input-mikofo | 20.1 ± 0.6 | 18.8 | 22.7 | 16.76 ± 4.70 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>165225049</pre>|<pre>108830766</pre>|
|input-lanjian|<pre>182619815</pre>|<pre>80747545</pre>|
|input-mattcl|<pre>170068701</pre>|<pre>78683433</pre>|
|input-mikofo|<pre>189527826</pre>|<pre>63013756</pre>|