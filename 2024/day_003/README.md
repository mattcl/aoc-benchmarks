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
| kcen | input-mattcl | 0.7 ± 0.4 | 0.0 | 1.8 | 1.00 |
| mattcl | input-mattcl | 1.1 ± 0.2 | 0.1 | 1.9 | 1.47 ± 0.88 |
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.2 | 1.4 | 1.55 ± 0.91 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.2 | 1.5 | 1.57 ± 0.92 |
| mattcl | input-mikofo | 1.2 ± 0.3 | 0.4 | 2.2 | 1.65 ± 0.98 |
| kcen | input-kcen | 1.3 ± 0.2 | 0.5 | 1.5 | 1.72 ± 0.98 |
| kcen | input-mikofo | 1.3 ± 0.2 | 0.6 | 1.8 | 1.74 ± 1.00 |
| kcen | input-lanjian | 1.3 ± 0.2 | 0.1 | 1.5 | 1.79 ± 1.02 |
| lanjian | input-mikofo | 1.7 ± 0.4 | 0.6 | 2.7 | 2.24 ± 1.38 |
| lanjian | input-mattcl | 1.8 ± 0.4 | 1.0 | 3.1 | 2.46 ± 1.46 |
| lanjian | input-kcen | 1.8 ± 0.3 | 1.3 | 2.5 | 2.47 ± 1.45 |
| lanjian | input-lanjian | 1.9 ± 0.3 | 0.9 | 2.5 | 2.57 ± 1.50 |
| mattcl-py | input-mikofo | 16.8 ± 0.6 | 15.5 | 20.2 | 22.48 ± 12.53 |
| mattcl-py | input-mattcl | 17.0 ± 0.7 | 16.1 | 20.5 | 22.78 ± 12.71 |
| mattcl-py | input-kcen | 17.2 ± 0.6 | 16.3 | 20.1 | 23.07 ± 12.86 |
| mattcl-py | input-lanjian | 17.7 ± 0.4 | 16.5 | 19.6 | 23.65 ± 13.17 |
| mikofo | input-mattcl | 19.5 ± 0.6 | 18.4 | 22.0 | 26.06 ± 14.52 |
| mikofo | input-mikofo | 19.6 ± 0.7 | 18.3 | 23.5 | 26.28 ± 14.66 |
| mikofo | input-lanjian | 20.2 ± 0.7 | 18.9 | 22.3 | 27.01 ± 15.05 |
| mikofo | input-kcen | 21.9 ± 3.0 | 19.0 | 30.6 | 29.25 ± 16.75 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>165225049</pre>|<pre>108830766</pre>|
|input-lanjian|<pre>182619815</pre>|<pre>80747545</pre>|
|input-mattcl|<pre>170068701</pre>|<pre>78683433</pre>|
|input-mikofo|<pre>189527826</pre>|<pre>63013756</pre>|