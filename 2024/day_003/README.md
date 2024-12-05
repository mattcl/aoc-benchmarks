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
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.4 | 1.8 | 1.00 |
| kcen | input-mattcl | 1.1 ± 0.2 | 0.5 | 1.8 | 1.04 ± 0.25 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.6 | 1.9 | 1.07 ± 0.27 |
| kcen | input-kcen | 1.2 ± 0.3 | 0.2 | 2.0 | 1.08 ± 0.30 |
| kcen | input-mikofo | 1.2 ± 0.2 | 0.5 | 1.9 | 1.08 ± 0.29 |
| mattcl | input-mattcl | 1.2 ± 0.3 | 0.2 | 2.1 | 1.09 ± 0.30 |
| mattcl | input-mikofo | 1.2 ± 0.2 | 0.6 | 2.3 | 1.09 ± 0.28 |
| kcen | input-lanjian | 1.2 ± 0.2 | 0.4 | 2.1 | 1.09 ± 0.28 |
| lanjian | input-kcen | 1.9 ± 0.3 | 1.1 | 2.8 | 1.68 ± 0.43 |
| lanjian | input-mattcl | 1.9 ± 0.3 | 1.2 | 2.8 | 1.72 ± 0.43 |
| lanjian | input-mikofo | 1.9 ± 0.3 | 1.2 | 2.7 | 1.72 ± 0.43 |
| lanjian | input-lanjian | 1.9 ± 0.4 | 0.9 | 3.1 | 1.74 ± 0.46 |
| mattcl-py | input-mikofo | 16.8 ± 0.6 | 16.0 | 20.0 | 15.26 ± 2.71 |
| mattcl-py | input-mattcl | 16.9 ± 0.6 | 15.7 | 19.7 | 15.28 ± 2.72 |
| mattcl-py | input-lanjian | 16.9 ± 0.6 | 15.9 | 20.4 | 15.34 ± 2.73 |
| mattcl-py | input-kcen | 17.0 ± 0.7 | 15.9 | 20.2 | 15.44 ± 2.78 |
| mikofo | input-kcen | 19.6 ± 0.6 | 18.5 | 22.9 | 17.75 ± 3.15 |
| mikofo | input-lanjian | 19.6 ± 0.6 | 18.5 | 22.4 | 17.78 ± 3.15 |
| mikofo | input-mattcl | 19.7 ± 0.6 | 18.6 | 22.2 | 17.83 ± 3.16 |
| mikofo | input-mikofo | 19.7 ± 0.7 | 18.3 | 22.7 | 17.84 ± 3.18 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>165225049</pre>|<pre>108830766</pre>|
|input-lanjian|<pre>182619815</pre>|<pre>80747545</pre>|
|input-mattcl|<pre>170068701</pre>|<pre>78683433</pre>|
|input-mikofo|<pre>189527826</pre>|<pre>63013756</pre>|