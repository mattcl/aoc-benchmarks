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
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.5 | 2.0 | 1.00 |
| mattcl | input-kcen | 1.3 ± 0.2 | 0.4 | 2.2 | 1.01 ± 0.24 |
| mattcl | input-mikofo | 1.3 ± 0.2 | 0.6 | 2.0 | 1.02 ± 0.26 |
| mattcl | input-lanjian | 1.3 ± 0.2 | 0.6 | 2.0 | 1.04 ± 0.23 |
| lanjian | input-kcen | 1.4 ± 0.2 | 0.9 | 2.3 | 1.08 ± 0.22 |
| lanjian | input-mattcl | 1.4 ± 0.2 | 0.9 | 2.7 | 1.08 ± 0.23 |
| lanjian | input-lanjian | 1.4 ± 0.2 | 0.6 | 2.6 | 1.11 ± 0.27 |
| lanjian | input-mikofo | 1.4 ± 0.2 | 0.4 | 2.3 | 1.11 ± 0.26 |
| kcen | input-mikofo | 2.2 ± 0.3 | 1.4 | 3.4 | 1.71 ± 0.40 |
| kcen | input-lanjian | 2.4 ± 0.3 | 1.4 | 3.1 | 1.83 ± 0.40 |
| kcen | input-kcen | 2.5 ± 0.3 | 1.4 | 3.6 | 1.95 ± 0.42 |
| kcen | input-mattcl | 2.6 ± 0.3 | 1.6 | 3.8 | 1.99 ± 0.41 |
| mattcl-py | input-lanjian | 17.5 ± 0.5 | 16.5 | 21.0 | 13.64 ± 2.38 |
| mattcl-py | input-kcen | 17.7 ± 0.7 | 16.3 | 21.3 | 13.80 ± 2.42 |
| mattcl-py | input-mikofo | 17.7 ± 0.8 | 16.6 | 21.0 | 13.80 ± 2.45 |
| mattcl-py | input-mattcl | 17.8 ± 0.7 | 16.3 | 20.6 | 13.83 ± 2.43 |
| mikofo | input-lanjian | 18.7 ± 0.7 | 17.3 | 21.7 | 14.52 ± 2.55 |
| mikofo | input-mikofo | 18.7 ± 0.9 | 17.6 | 22.3 | 14.52 ± 2.58 |
| mikofo | input-mattcl | 18.9 ± 0.7 | 17.5 | 22.1 | 14.74 ± 2.58 |
| mikofo | input-kcen | 19.0 ± 0.8 | 17.2 | 22.1 | 14.74 ± 2.61 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5955</pre>|<pre>4030</pre>|
|input-lanjian|<pre>5509</pre>|<pre>4407</pre>|
|input-mattcl|<pre>4996</pre>|<pre>6311</pre>|
|input-mikofo|<pre>7198</pre>|<pre>4230</pre>|