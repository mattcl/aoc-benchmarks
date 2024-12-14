# Day 4 benchmarks

[link to problem](https://adventofcode.com/2024/day/4)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2024)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 4)

- [kcen](https://github.com/kcen/aoc2024) (nim)
- [lanjian](https://github.com/lanjian/aoc-2024) (rust)
- [mattcl](https://github.com/mattcl/aoc2024) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2024-py) (python)
- [mikofo](https://github.com/mikofo/aoc2024) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-kcen | 1.6 ± 0.3 | 1.0 | 2.7 | 1.00 |
| lanjian | input-mattcl | 1.6 ± 0.3 | 0.7 | 2.4 | 1.00 ± 0.28 |
| lanjian | input-mikofo | 1.6 ± 0.3 | 1.0 | 2.6 | 1.00 ± 0.28 |
| lanjian | input-kcen | 1.7 ± 0.3 | 0.9 | 2.6 | 1.01 ± 0.27 |
| mattcl | input-mikofo | 1.7 ± 0.3 | 1.0 | 3.0 | 1.02 ± 0.29 |
| mattcl | input-lanjian | 1.7 ± 0.4 | 0.9 | 2.9 | 1.03 ± 0.30 |
| lanjian | input-lanjian | 1.7 ± 0.4 | 0.9 | 2.6 | 1.03 ± 0.30 |
| mattcl | input-mattcl | 1.7 ± 0.4 | 1.0 | 2.8 | 1.04 ± 0.30 |
| kcen | input-lanjian | 2.4 ± 0.3 | 1.5 | 3.1 | 1.47 ± 0.33 |
| kcen | input-kcen | 2.4 ± 0.3 | 1.4 | 4.2 | 1.47 ± 0.35 |
| kcen | input-mikofo | 2.4 ± 0.3 | 1.5 | 3.5 | 1.48 ± 0.35 |
| kcen | input-mattcl | 2.5 ± 0.3 | 1.6 | 3.5 | 1.50 ± 0.33 |
| mattcl-py | input-kcen | 22.8 ± 0.6 | 21.9 | 25.4 | 13.88 ± 2.67 |
| mattcl-py | input-mattcl | 22.9 ± 0.6 | 21.8 | 25.1 | 13.93 ± 2.68 |
| mattcl-py | input-mikofo | 22.9 ± 0.8 | 21.8 | 25.9 | 13.95 ± 2.71 |
| mattcl-py | input-lanjian | 23.0 ± 1.3 | 21.7 | 35.6 | 14.00 ± 2.79 |
| mikofo | input-kcen | 26.3 ± 0.8 | 24.9 | 30.0 | 16.03 ± 3.10 |
| mikofo | input-mattcl | 26.5 ± 0.7 | 25.4 | 28.8 | 16.14 ± 3.11 |
| mikofo | input-lanjian | 26.5 ± 0.8 | 24.8 | 29.3 | 16.14 ± 3.12 |
| mikofo | input-mikofo | 26.5 ± 1.1 | 24.7 | 29.4 | 16.17 ± 3.15 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>2521</pre>|<pre>1912</pre>|
|input-lanjian|<pre>2646</pre>|<pre>2000</pre>|
|input-mattcl|<pre>2573</pre>|<pre>1850</pre>|
|input-mikofo|<pre>2336</pre>|<pre>1831</pre>|