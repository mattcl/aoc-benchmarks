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
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.6 | 2.1 | 1.00 |
| kcen | input-mattcl | 1.1 ± 0.2 | 0.1 | 1.8 | 1.00 ± 0.29 |
| mattcl | input-kcen | 1.1 ± 0.2 | 0.4 | 2.0 | 1.03 ± 0.27 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.5 | 1.9 | 1.03 ± 0.27 |
| kcen | input-mikofo | 1.2 ± 0.2 | 0.5 | 2.2 | 1.04 ± 0.28 |
| kcen | input-kcen | 1.2 ± 0.2 | 0.4 | 1.8 | 1.06 ± 0.29 |
| mattcl | input-mikofo | 1.2 ± 0.2 | 0.5 | 2.1 | 1.09 ± 0.30 |
| kcen | input-lanjian | 1.2 ± 0.3 | 0.1 | 2.5 | 1.10 ± 0.32 |
| lanjian | input-kcen | 1.9 ± 0.3 | 1.2 | 2.6 | 1.72 ± 0.45 |
| lanjian | input-mattcl | 1.9 ± 0.4 | 1.1 | 3.0 | 1.73 ± 0.46 |
| lanjian | input-mikofo | 1.9 ± 0.3 | 1.1 | 2.9 | 1.74 ± 0.46 |
| lanjian | input-lanjian | 1.9 ± 0.3 | 1.2 | 2.7 | 1.74 ± 0.45 |
| mattcl-py | input-lanjian | 17.1 ± 0.6 | 15.8 | 19.8 | 15.37 ± 3.00 |
| mattcl-py | input-mikofo | 17.1 ± 0.6 | 16.2 | 19.9 | 15.37 ± 3.00 |
| mattcl-py | input-kcen | 17.1 ± 0.7 | 15.9 | 20.1 | 15.38 ± 3.01 |
| mattcl-py | input-mattcl | 17.2 ± 0.8 | 16.3 | 20.5 | 15.49 ± 3.04 |
| mikofo | input-kcen | 19.8 ± 0.7 | 18.5 | 22.9 | 17.81 ± 3.47 |
| mikofo | input-mikofo | 19.9 ± 0.6 | 19.0 | 22.7 | 17.90 ± 3.46 |
| mikofo | input-mattcl | 19.9 ± 0.8 | 18.7 | 23.2 | 17.91 ± 3.50 |
| mikofo | input-lanjian | 20.1 ± 1.0 | 19.0 | 28.8 | 18.05 ± 3.56 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>165225049</pre>|<pre>108830766</pre>|
|input-lanjian|<pre>182619815</pre>|<pre>80747545</pre>|
|input-mattcl|<pre>170068701</pre>|<pre>78683433</pre>|
|input-mikofo|<pre>189527826</pre>|<pre>63013756</pre>|