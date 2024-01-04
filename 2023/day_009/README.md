# Day 9 benchmarks

[link to problem](https://adventofcode.com/2023/day/9)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 9)

- [kcen](https://github.com/kcen/aoc2023) (python)
- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [mattcl-ts](https://github.com/mattcl/aoc2023-js) (typescript (bun))
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.2 | 1.2 | 1.00 |
| mattcl | input-lanjian | 1.0 ± 0.1 | 0.3 | 1.2 | 1.04 ± 0.22 |
| mattcl | input-pting | 1.0 ± 0.2 | 0.4 | 1.7 | 1.05 ± 0.25 |
| mattcl | input-kcen | 1.0 ± 0.1 | 0.5 | 1.7 | 1.06 ± 0.23 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.8 | 1.7 | 1.07 ± 0.30 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.7 | 1.8 | 1.08 ± 0.29 |
| lanjian | input-pting | 1.1 ± 0.2 | 0.7 | 1.7 | 1.09 ± 0.30 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.8 | 1.6 | 1.10 ± 0.31 |
| mattcl-ts | input-pting | 12.2 ± 0.4 | 11.0 | 13.6 | 12.40 ± 2.16 |
| mattcl-ts | input-mattcl | 12.3 ± 0.4 | 11.3 | 13.4 | 12.51 ± 2.18 |
| mattcl-ts | input-kcen | 12.3 ± 0.4 | 11.2 | 13.1 | 12.52 ± 2.18 |
| mattcl-ts | input-lanjian | 12.7 ± 3.7 | 11.2 | 49.8 | 12.88 ± 4.38 |
| mattcl-py | input-kcen | 15.1 ± 0.4 | 14.1 | 17.8 | 15.34 ± 2.66 |
| mattcl-py | input-mattcl | 15.2 ± 0.6 | 14.2 | 18.5 | 15.41 ± 2.71 |
| mattcl-py | input-lanjian | 15.2 ± 0.6 | 14.0 | 18.0 | 15.42 ± 2.71 |
| mattcl-py | input-pting | 15.2 ± 0.6 | 14.1 | 18.0 | 15.42 ± 2.71 |
| pting | input-pting | 16.1 ± 0.6 | 15.0 | 19.0 | 16.38 ± 2.88 |
| pting | input-kcen | 16.2 ± 0.7 | 15.2 | 19.9 | 16.50 ± 2.90 |
| pting | input-mattcl | 16.3 ± 0.8 | 15.2 | 19.1 | 16.58 ± 2.94 |
| pting | input-lanjian | 16.3 ± 0.7 | 15.2 | 19.5 | 16.59 ± 2.93 |
| kcen | input-pting | 17.3 ± 0.7 | 16.1 | 20.8 | 17.61 ± 3.11 |
| kcen | input-kcen | 17.5 ± 0.6 | 16.7 | 20.8 | 17.81 ± 3.11 |
| kcen | input-lanjian | 17.6 ± 0.8 | 16.5 | 20.4 | 17.83 ± 3.15 |
| kcen | input-mattcl | 17.6 ± 0.7 | 16.5 | 20.0 | 17.85 ± 3.14 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>1938800261</pre>|<pre>1112</pre>|
|input-lanjian|<pre>2075724761</pre>|<pre>1072</pre>|
|input-mattcl|<pre>1969958987</pre>|<pre>1068</pre>|
|input-pting|<pre>1584748274</pre>|<pre>1026</pre>|