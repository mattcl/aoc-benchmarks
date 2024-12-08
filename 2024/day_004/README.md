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
| mattcl | input-lanjian | 1.5 ± 0.2 | 0.8 | 2.3 | 1.00 |
| lanjian | input-mattcl | 1.5 ± 0.2 | 1.0 | 2.3 | 1.00 ± 0.20 |
| lanjian | input-lanjian | 1.5 ± 0.2 | 1.0 | 2.5 | 1.01 ± 0.21 |
| lanjian | input-kcen | 1.5 ± 0.3 | 0.7 | 2.5 | 1.02 ± 0.23 |
| mattcl | input-mattcl | 1.5 ± 0.2 | 1.0 | 2.7 | 1.02 ± 0.21 |
| mattcl | input-kcen | 1.5 ± 0.3 | 0.8 | 2.4 | 1.02 ± 0.24 |
| mattcl | input-mikofo | 1.5 ± 0.3 | 0.6 | 2.6 | 1.02 ± 0.25 |
| lanjian | input-mikofo | 1.6 ± 0.3 | 1.0 | 2.7 | 1.06 ± 0.25 |
| kcen | input-lanjian | 2.0 ± 0.3 | 1.2 | 3.0 | 1.37 ± 0.30 |
| kcen | input-kcen | 2.0 ± 0.4 | 1.1 | 3.0 | 1.37 ± 0.30 |
| kcen | input-mattcl | 2.0 ± 0.3 | 1.3 | 3.0 | 1.37 ± 0.29 |
| kcen | input-mikofo | 2.0 ± 0.3 | 1.3 | 2.9 | 1.38 ± 0.30 |
| mattcl-py | input-kcen | 22.7 ± 0.6 | 21.6 | 26.0 | 15.27 ± 2.17 |
| mattcl-py | input-lanjian | 22.7 ± 0.7 | 21.7 | 25.5 | 15.28 ± 2.17 |
| mattcl-py | input-mikofo | 22.7 ± 0.8 | 21.5 | 26.0 | 15.33 ± 2.20 |
| mattcl-py | input-mattcl | 22.8 ± 0.8 | 21.8 | 26.0 | 15.36 ± 2.21 |
| mikofo | input-kcen | 25.9 ± 0.8 | 24.8 | 29.3 | 17.48 ± 2.50 |
| mikofo | input-lanjian | 26.2 ± 0.9 | 25.0 | 29.2 | 17.63 ± 2.52 |
| mikofo | input-mikofo | 26.2 ± 1.0 | 25.0 | 30.0 | 17.66 ± 2.54 |
| mikofo | input-mattcl | 26.3 ± 0.9 | 25.3 | 31.1 | 17.74 ± 2.54 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>2521</pre>|<pre>1912</pre>|
|input-lanjian|<pre>2646</pre>|<pre>2000</pre>|
|input-mattcl|<pre>2573</pre>|<pre>1850</pre>|
|input-mikofo|<pre>2336</pre>|<pre>1831</pre>|