# Day 5 benchmarks

[link to problem](https://adventofcode.com/2024/day/5)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2024)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 5)

- [kcen](https://github.com/kcen/aoc2024) (nim)
- [lanjian](https://github.com/lanjian/aoc-2024) (rust)
- [mattcl](https://github.com/mattcl/aoc2024) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2024-py) (python)
- [mikofo](https://github.com/mikofo/aoc2024) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-mattcl | 1.4 ± 0.2 | 0.5 | 1.8 | 1.00 |
| mattcl | input-kcen | 1.4 ± 0.1 | 0.7 | 1.8 | 1.01 ± 0.16 |
| mattcl | input-mikofo | 1.4 ± 0.1 | 0.6 | 1.7 | 1.01 ± 0.17 |
| mattcl | input-lanjian | 1.4 ± 0.2 | 0.6 | 2.6 | 1.02 ± 0.21 |
| lanjian | input-mattcl | 1.4 ± 0.1 | 0.9 | 2.0 | 1.03 ± 0.16 |
| lanjian | input-kcen | 1.5 ± 0.2 | 0.4 | 2.3 | 1.07 ± 0.20 |
| lanjian | input-mikofo | 1.5 ± 0.3 | 0.8 | 2.6 | 1.08 ± 0.23 |
| lanjian | input-lanjian | 1.5 ± 0.3 | 0.8 | 2.7 | 1.08 ± 0.24 |
| kcen | input-mikofo | 2.6 ± 0.3 | 1.6 | 4.6 | 1.88 ± 0.34 |
| kcen | input-lanjian | 2.6 ± 0.5 | 1.6 | 5.2 | 1.90 ± 0.41 |
| kcen | input-kcen | 2.6 ± 0.2 | 1.8 | 4.7 | 1.90 ± 0.30 |
| kcen | input-mattcl | 2.7 ± 0.3 | 1.9 | 5.1 | 1.94 ± 0.35 |
| mattcl-py | input-mikofo | 17.5 ± 0.5 | 16.4 | 20.0 | 12.71 ± 1.68 |
| mattcl-py | input-mattcl | 17.6 ± 0.7 | 16.5 | 20.6 | 12.84 ± 1.73 |
| mattcl-py | input-lanjian | 17.7 ± 0.7 | 16.6 | 20.5 | 12.87 ± 1.74 |
| mattcl-py | input-kcen | 17.7 ± 0.8 | 16.5 | 20.7 | 12.90 ± 1.76 |
| mikofo | input-mikofo | 18.4 ± 0.6 | 17.1 | 21.3 | 13.43 ± 1.79 |
| mikofo | input-lanjian | 18.6 ± 0.6 | 17.3 | 21.6 | 13.57 ± 1.81 |
| mikofo | input-mattcl | 18.8 ± 0.5 | 17.7 | 21.6 | 13.70 ± 1.81 |
| mikofo | input-kcen | 18.8 ± 0.7 | 17.4 | 21.9 | 13.73 ± 1.85 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5955</pre>|<pre>4030</pre>|
|input-lanjian|<pre>5509</pre>|<pre>4407</pre>|
|input-mattcl|<pre>4996</pre>|<pre>6311</pre>|
|input-mikofo|<pre>7198</pre>|<pre>4230</pre>|