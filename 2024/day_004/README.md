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
| mattcl | input-mattcl | 1.5 ± 0.3 | 0.5 | 2.7 | 1.00 |
| lanjian | input-lanjian | 1.5 ± 0.2 | 1.0 | 2.7 | 1.00 ± 0.24 |
| lanjian | input-mattcl | 1.5 ± 0.2 | 0.7 | 2.6 | 1.01 ± 0.24 |
| mattcl | input-lanjian | 1.5 ± 0.3 | 0.8 | 2.5 | 1.01 ± 0.25 |
| lanjian | input-mikofo | 1.6 ± 0.3 | 1.0 | 2.7 | 1.03 ± 0.27 |
| mattcl | input-mikofo | 1.6 ± 0.3 | 0.7 | 2.6 | 1.03 ± 0.28 |
| mattcl | input-kcen | 1.6 ± 0.3 | 1.0 | 2.7 | 1.04 ± 0.28 |
| lanjian | input-kcen | 1.6 ± 0.3 | 0.9 | 2.7 | 1.04 ± 0.28 |
| kcen | input-mattcl | 2.0 ± 0.4 | 1.3 | 3.2 | 1.35 ± 0.34 |
| kcen | input-mikofo | 2.1 ± 0.3 | 1.3 | 2.9 | 1.36 ± 0.32 |
| kcen | input-lanjian | 2.1 ± 0.3 | 1.3 | 3.4 | 1.37 ± 0.34 |
| kcen | input-kcen | 2.1 ± 0.3 | 1.1 | 3.2 | 1.38 ± 0.33 |
| mattcl-py | input-mikofo | 22.7 ± 0.7 | 21.6 | 25.9 | 15.04 ± 2.72 |
| mattcl-py | input-mattcl | 22.8 ± 0.7 | 21.5 | 26.0 | 15.06 ± 2.72 |
| mattcl-py | input-kcen | 22.8 ± 1.4 | 21.6 | 36.8 | 15.06 ± 2.84 |
| mattcl-py | input-lanjian | 22.8 ± 1.3 | 21.8 | 34.2 | 15.07 ± 2.81 |
| mikofo | input-mikofo | 26.0 ± 0.7 | 24.6 | 28.9 | 17.16 ± 3.09 |
| mikofo | input-kcen | 26.2 ± 0.9 | 25.1 | 29.4 | 17.34 ± 3.15 |
| mikofo | input-lanjian | 26.2 ± 0.8 | 24.7 | 28.9 | 17.35 ± 3.14 |
| mikofo | input-mattcl | 26.5 ± 1.0 | 25.2 | 29.7 | 17.54 ± 3.20 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>2521</pre>|<pre>1912</pre>|
|input-lanjian|<pre>2646</pre>|<pre>2000</pre>|
|input-mattcl|<pre>2573</pre>|<pre>1850</pre>|
|input-mikofo|<pre>2336</pre>|<pre>1831</pre>|