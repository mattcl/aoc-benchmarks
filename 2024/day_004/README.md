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
| mattcl | input-lanjian | 1.6 ± 0.3 | 0.9 | 2.7 | 1.00 |
| lanjian | input-lanjian | 1.6 ± 0.3 | 0.8 | 2.7 | 1.00 ± 0.27 |
| lanjian | input-mikofo | 1.7 ± 0.3 | 1.0 | 2.8 | 1.01 ± 0.27 |
| mattcl | input-mikofo | 1.7 ± 0.4 | 0.7 | 2.8 | 1.02 ± 0.29 |
| lanjian | input-mattcl | 1.7 ± 0.4 | 1.1 | 2.6 | 1.04 ± 0.30 |
| lanjian | input-kcen | 1.7 ± 0.3 | 0.8 | 2.7 | 1.04 ± 0.29 |
| mattcl | input-kcen | 1.7 ± 0.4 | 0.9 | 3.0 | 1.05 ± 0.30 |
| mattcl | input-mattcl | 1.7 ± 0.4 | 1.0 | 2.9 | 1.06 ± 0.31 |
| kcen | input-lanjian | 2.4 ± 0.3 | 1.4 | 3.0 | 1.47 ± 0.32 |
| kcen | input-kcen | 2.4 ± 0.3 | 1.5 | 4.0 | 1.48 ± 0.33 |
| kcen | input-mattcl | 2.5 ± 0.3 | 1.5 | 3.9 | 1.50 ± 0.34 |
| kcen | input-mikofo | 2.5 ± 0.3 | 1.4 | 3.6 | 1.50 ± 0.33 |
| mattcl-py | input-lanjian | 22.8 ± 0.7 | 21.9 | 25.9 | 13.89 ± 2.61 |
| mattcl-py | input-mikofo | 22.9 ± 0.8 | 21.6 | 26.6 | 13.93 ± 2.63 |
| mattcl-py | input-kcen | 22.9 ± 0.9 | 21.6 | 26.8 | 13.98 ± 2.65 |
| mattcl-py | input-mattcl | 23.0 ± 0.9 | 21.7 | 26.5 | 14.00 ± 2.65 |
| mikofo | input-kcen | 26.2 ± 0.7 | 24.8 | 29.2 | 15.95 ± 2.99 |
| mikofo | input-mikofo | 26.3 ± 0.9 | 24.8 | 29.3 | 16.00 ± 3.02 |
| mikofo | input-lanjian | 26.4 ± 0.9 | 25.2 | 29.7 | 16.07 ± 3.03 |
| mikofo | input-mattcl | 26.5 ± 0.7 | 24.9 | 29.6 | 16.13 ± 3.03 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>2521</pre>|<pre>1912</pre>|
|input-lanjian|<pre>2646</pre>|<pre>2000</pre>|
|input-mattcl|<pre>2573</pre>|<pre>1850</pre>|
|input-mikofo|<pre>2336</pre>|<pre>1831</pre>|