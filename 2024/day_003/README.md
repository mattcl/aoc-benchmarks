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
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.6 | 2.6 | 1.00 |
| mattcl | input-kcen | 1.3 ± 0.2 | 0.6 | 2.2 | 1.01 ± 0.26 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.2 | 2.0 | 1.01 ± 0.25 |
| mattcl | input-mikofo | 1.3 ± 0.2 | 0.4 | 2.1 | 1.03 ± 0.27 |
| kcen | input-mattcl | 1.4 ± 0.2 | 0.6 | 2.0 | 1.12 ± 0.24 |
| kcen | input-kcen | 1.4 ± 0.2 | 0.6 | 1.9 | 1.12 ± 0.25 |
| kcen | input-mikofo | 1.4 ± 0.2 | 0.7 | 2.1 | 1.12 ± 0.25 |
| kcen | input-lanjian | 1.4 ± 0.2 | 0.7 | 2.0 | 1.12 ± 0.25 |
| lanjian | input-mattcl | 2.0 ± 0.3 | 1.3 | 3.7 | 1.59 ± 0.39 |
| lanjian | input-lanjian | 2.0 ± 0.4 | 0.8 | 3.0 | 1.59 ± 0.40 |
| lanjian | input-mikofo | 2.0 ± 0.4 | 1.0 | 3.2 | 1.59 ± 0.41 |
| lanjian | input-kcen | 2.0 ± 0.4 | 1.2 | 3.4 | 1.61 ± 0.42 |
| mattcl-py | input-mikofo | 17.1 ± 0.7 | 16.3 | 20.5 | 13.56 ± 2.52 |
| mattcl-py | input-lanjian | 17.2 ± 0.7 | 16.3 | 20.7 | 13.57 ± 2.52 |
| mattcl-py | input-kcen | 17.2 ± 0.7 | 16.2 | 20.2 | 13.59 ± 2.52 |
| mattcl-py | input-mattcl | 17.2 ± 0.6 | 16.2 | 20.0 | 13.62 ± 2.52 |
| mikofo | input-kcen | 19.8 ± 0.5 | 18.8 | 22.4 | 15.66 ± 2.87 |
| mikofo | input-mattcl | 20.0 ± 0.6 | 18.4 | 23.5 | 15.83 ± 2.91 |
| mikofo | input-mikofo | 20.0 ± 0.7 | 18.9 | 22.8 | 15.86 ± 2.92 |
| mikofo | input-lanjian | 20.1 ± 0.7 | 18.8 | 23.2 | 15.91 ± 2.94 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>165225049</pre>|<pre>108830766</pre>|
|input-lanjian|<pre>182619815</pre>|<pre>80747545</pre>|
|input-mattcl|<pre>170068701</pre>|<pre>78683433</pre>|
|input-mikofo|<pre>189527826</pre>|<pre>63013756</pre>|