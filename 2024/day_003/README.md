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
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.6 | 1.9 | 1.00 |
| kcen | input-kcen | 1.2 ± 0.2 | 0.5 | 1.9 | 1.03 ± 0.25 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.5 | 2.0 | 1.04 ± 0.26 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.6 | 2.0 | 1.05 ± 0.26 |
| mattcl | input-mikofo | 1.3 ± 0.2 | 0.7 | 2.0 | 1.07 ± 0.25 |
| kcen | input-mattcl | 1.3 ± 0.2 | 0.6 | 1.9 | 1.08 ± 0.26 |
| kcen | input-mikofo | 1.3 ± 0.3 | 0.5 | 2.5 | 1.10 ± 0.29 |
| kcen | input-lanjian | 1.3 ± 0.3 | 0.5 | 2.6 | 1.10 ± 0.29 |
| lanjian | input-mikofo | 2.0 ± 0.4 | 0.9 | 2.9 | 1.69 ± 0.43 |
| lanjian | input-kcen | 2.0 ± 0.3 | 1.4 | 2.9 | 1.72 ± 0.40 |
| lanjian | input-lanjian | 2.0 ± 0.4 | 1.1 | 3.4 | 1.73 ± 0.43 |
| lanjian | input-mattcl | 2.0 ± 0.4 | 1.1 | 3.0 | 1.75 ± 0.43 |
| mattcl-py | input-mikofo | 17.2 ± 0.7 | 16.0 | 21.1 | 14.74 ± 2.48 |
| mattcl-py | input-lanjian | 17.2 ± 0.7 | 16.3 | 20.2 | 14.77 ± 2.48 |
| mattcl-py | input-kcen | 17.2 ± 0.7 | 16.3 | 20.2 | 14.78 ± 2.48 |
| mattcl-py | input-mattcl | 17.3 ± 0.7 | 16.3 | 20.4 | 14.80 ± 2.48 |
| mikofo | input-kcen | 19.9 ± 0.7 | 18.9 | 22.8 | 17.08 ± 2.84 |
| mikofo | input-mattcl | 20.1 ± 0.5 | 18.9 | 22.3 | 17.18 ± 2.83 |
| mikofo | input-lanjian | 20.1 ± 0.7 | 19.0 | 23.0 | 17.21 ± 2.87 |
| mikofo | input-mikofo | 20.1 ± 0.7 | 18.8 | 22.9 | 17.22 ± 2.86 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>165225049</pre>|<pre>108830766</pre>|
|input-lanjian|<pre>182619815</pre>|<pre>80747545</pre>|
|input-mattcl|<pre>170068701</pre>|<pre>78683433</pre>|
|input-mikofo|<pre>189527826</pre>|<pre>63013756</pre>|