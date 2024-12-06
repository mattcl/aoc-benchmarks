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
| mattcl | input-kcen | 1.1 ± 0.2 | 0.5 | 1.8 | 1.00 |
| kcen | input-kcen | 1.2 ± 0.2 | 0.5 | 1.9 | 1.02 ± 0.26 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.5 | 1.9 | 1.02 ± 0.25 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.4 | 2.1 | 1.05 ± 0.25 |
| kcen | input-lanjian | 1.2 ± 0.2 | 0.5 | 1.9 | 1.05 ± 0.28 |
| kcen | input-mattcl | 1.2 ± 0.2 | 0.4 | 2.1 | 1.05 ± 0.27 |
| mattcl | input-mikofo | 1.2 ± 0.2 | 0.5 | 2.1 | 1.06 ± 0.28 |
| kcen | input-mikofo | 1.2 ± 0.2 | 0.6 | 2.2 | 1.08 ± 0.27 |
| lanjian | input-mattcl | 1.9 ± 0.4 | 1.2 | 2.9 | 1.67 ± 0.42 |
| lanjian | input-kcen | 1.9 ± 0.4 | 0.8 | 2.7 | 1.68 ± 0.43 |
| lanjian | input-lanjian | 1.9 ± 0.4 | 1.2 | 3.0 | 1.69 ± 0.43 |
| lanjian | input-mikofo | 2.0 ± 0.3 | 1.1 | 2.9 | 1.73 ± 0.42 |
| mattcl-py | input-mikofo | 17.0 ± 0.6 | 15.8 | 20.1 | 14.87 ± 2.64 |
| mattcl-py | input-lanjian | 17.1 ± 0.6 | 16.4 | 20.4 | 14.98 ± 2.65 |
| mattcl-py | input-mattcl | 17.1 ± 0.7 | 16.0 | 20.5 | 14.98 ± 2.66 |
| mattcl-py | input-kcen | 17.2 ± 0.6 | 16.0 | 19.8 | 15.09 ± 2.67 |
| mikofo | input-mattcl | 19.8 ± 0.5 | 18.4 | 21.7 | 17.36 ± 3.05 |
| mikofo | input-kcen | 19.9 ± 0.7 | 18.3 | 22.5 | 17.40 ± 3.08 |
| mikofo | input-mikofo | 20.0 ± 0.7 | 18.4 | 23.1 | 17.48 ± 3.10 |
| mikofo | input-lanjian | 20.0 ± 0.9 | 18.3 | 23.1 | 17.49 ± 3.13 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>165225049</pre>|<pre>108830766</pre>|
|input-lanjian|<pre>182619815</pre>|<pre>80747545</pre>|
|input-mattcl|<pre>170068701</pre>|<pre>78683433</pre>|
|input-mikofo|<pre>189527826</pre>|<pre>63013756</pre>|