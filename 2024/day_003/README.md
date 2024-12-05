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
| kcen | input-lanjian | 1.1 ± 0.2 | 0.5 | 1.8 | 1.00 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.5 | 1.9 | 1.01 ± 0.23 |
| mattcl | input-kcen | 1.1 ± 0.2 | 0.3 | 1.9 | 1.02 ± 0.23 |
| mattcl | input-mattcl | 1.2 ± 0.2 | 0.1 | 2.2 | 1.03 ± 0.26 |
| mattcl | input-mikofo | 1.2 ± 0.2 | 0.5 | 1.9 | 1.03 ± 0.23 |
| kcen | input-kcen | 1.2 ± 0.2 | 0.2 | 2.2 | 1.05 ± 0.27 |
| kcen | input-mattcl | 1.2 ± 0.2 | 0.5 | 2.0 | 1.10 ± 0.26 |
| kcen | input-mikofo | 1.3 ± 0.2 | 0.7 | 2.1 | 1.12 ± 0.24 |
| lanjian | input-mattcl | 1.9 ± 0.4 | 1.0 | 3.1 | 1.72 ± 0.40 |
| lanjian | input-kcen | 1.9 ± 0.4 | 1.2 | 2.8 | 1.74 ± 0.41 |
| lanjian | input-mikofo | 2.0 ± 0.4 | 1.0 | 3.2 | 1.74 ± 0.41 |
| lanjian | input-lanjian | 2.0 ± 0.3 | 1.3 | 2.9 | 1.74 ± 0.38 |
| mattcl-py | input-lanjian | 17.0 ± 0.5 | 16.0 | 19.6 | 15.17 ± 2.30 |
| mattcl-py | input-mattcl | 17.1 ± 0.6 | 16.1 | 20.6 | 15.25 ± 2.33 |
| mattcl-py | input-mikofo | 17.1 ± 0.6 | 16.2 | 20.2 | 15.26 ± 2.33 |
| mattcl-py | input-kcen | 17.2 ± 0.7 | 16.4 | 21.0 | 15.30 ± 2.35 |
| mikofo | input-kcen | 19.8 ± 0.7 | 18.8 | 23.0 | 17.66 ± 2.70 |
| mikofo | input-lanjian | 19.9 ± 0.9 | 18.4 | 23.2 | 17.70 ± 2.73 |
| mikofo | input-mikofo | 20.0 ± 0.8 | 18.3 | 23.5 | 17.76 ± 2.72 |
| mikofo | input-mattcl | 20.0 ± 0.7 | 18.8 | 22.7 | 17.78 ± 2.70 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>165225049</pre>|<pre>108830766</pre>|
|input-lanjian|<pre>182619815</pre>|<pre>80747545</pre>|
|input-mattcl|<pre>170068701</pre>|<pre>78683433</pre>|
|input-mikofo|<pre>189527826</pre>|<pre>63013756</pre>|