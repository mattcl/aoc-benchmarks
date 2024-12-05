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
| mattcl | input-lanjian | 1.2 ± 0.2 | 0.4 | 1.5 | 1.00 |
| mattcl | input-kcen | 1.2 ± 0.2 | 0.5 | 1.4 | 1.03 ± 0.24 |
| mattcl | input-mikofo | 1.3 ± 0.2 | 0.6 | 1.5 | 1.05 ± 0.25 |
| mattcl | input-mattcl | 1.3 ± 0.2 | 0.0 | 1.6 | 1.05 ± 0.28 |
| lanjian | input-mattcl | 1.3 ± 0.2 | 0.3 | 2.3 | 1.12 ± 0.30 |
| lanjian | input-lanjian | 1.4 ± 0.2 | 0.7 | 2.1 | 1.14 ± 0.26 |
| lanjian | input-kcen | 1.4 ± 0.2 | 0.4 | 2.3 | 1.14 ± 0.26 |
| lanjian | input-mikofo | 1.4 ± 0.2 | 0.7 | 2.3 | 1.16 ± 0.27 |
| kcen | input-mikofo | 2.3 ± 0.3 | 1.2 | 2.9 | 1.90 ± 0.46 |
| kcen | input-lanjian | 2.3 ± 0.3 | 1.1 | 3.4 | 1.96 ± 0.45 |
| kcen | input-kcen | 2.5 ± 0.2 | 1.6 | 3.6 | 2.08 ± 0.44 |
| kcen | input-mattcl | 3.6 ± 2.8 | 1.2 | 15.4 | 2.97 ± 2.44 |
| mattcl-py | input-lanjian | 17.8 ± 0.6 | 16.6 | 20.3 | 14.89 ± 2.88 |
| mattcl-py | input-kcen | 17.9 ± 0.5 | 16.9 | 20.7 | 14.97 ± 2.88 |
| mattcl-py | input-mattcl | 17.9 ± 0.5 | 16.8 | 20.6 | 14.97 ± 2.88 |
| mikofo | input-mikofo | 18.9 ± 0.4 | 17.9 | 20.5 | 15.76 ± 3.02 |
| mikofo | input-lanjian | 18.9 ± 0.5 | 17.8 | 21.4 | 15.77 ± 3.03 |
| mattcl-py | input-mikofo | 19.0 ± 3.1 | 16.8 | 34.0 | 15.90 ± 4.01 |
| mikofo | input-mattcl | 19.2 ± 0.5 | 18.1 | 21.4 | 16.04 ± 3.08 |
| mikofo | input-kcen | 20.8 ± 4.2 | 18.0 | 36.0 | 17.35 ± 4.84 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>5955</pre>|<pre>4030</pre>|
|input-lanjian|<pre>5509</pre>|<pre>4407</pre>|
|input-mattcl|<pre>4996</pre>|<pre>6311</pre>|
|input-mikofo|<pre>7198</pre>|<pre>4230</pre>|