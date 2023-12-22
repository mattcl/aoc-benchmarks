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
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.5 | 1.00 |
| mattcl | input-mattcl | 0.9 ± 0.1 | 0.3 | 1.1 | 1.04 ± 0.29 |
| mattcl | input-kcen | 0.9 ± 0.1 | 0.5 | 1.5 | 1.05 ± 0.29 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.2 | 1.7 | 1.06 ± 0.30 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.7 | 2.2 | 1.11 ± 0.37 |
| lanjian | input-mattcl | 1.0 ± 0.2 | 0.7 | 1.7 | 1.11 ± 0.37 |
| lanjian | input-pting | 1.0 ± 0.2 | 0.6 | 1.5 | 1.14 ± 0.38 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.7 | 1.7 | 1.15 ± 0.37 |
| mattcl-ts | input-pting | 12.4 ± 0.3 | 11.3 | 13.1 | 13.92 ± 3.22 |
| mattcl-ts | input-mattcl | 12.5 ± 0.3 | 11.5 | 13.5 | 13.95 ± 3.23 |
| mattcl-ts | input-lanjian | 12.5 ± 0.4 | 11.4 | 13.3 | 13.95 ± 3.23 |
| mattcl-ts | input-kcen | 12.5 ± 0.3 | 11.4 | 13.5 | 14.01 ± 3.24 |
| mattcl-py | input-kcen | 15.1 ± 0.6 | 14.1 | 18.1 | 16.91 ± 3.94 |
| mattcl-py | input-pting | 15.1 ± 0.5 | 14.2 | 18.3 | 16.93 ± 3.93 |
| mattcl-py | input-lanjian | 15.1 ± 0.5 | 14.1 | 17.8 | 16.93 ± 3.93 |
| mattcl-py | input-mattcl | 15.1 ± 0.6 | 14.2 | 18.6 | 16.95 ± 3.95 |
| pting | input-kcen | 16.2 ± 0.6 | 15.1 | 18.6 | 18.09 ± 4.21 |
| pting | input-pting | 16.2 ± 0.6 | 15.3 | 19.8 | 18.10 ± 4.23 |
| pting | input-mattcl | 16.3 ± 0.6 | 15.0 | 18.7 | 18.22 ± 4.25 |
| pting | input-lanjian | 16.4 ± 1.8 | 15.1 | 38.6 | 18.35 ± 4.68 |
| kcen | input-pting | 17.3 ± 0.6 | 16.4 | 20.1 | 19.40 ± 4.51 |
| kcen | input-kcen | 17.5 ± 0.7 | 16.7 | 20.8 | 19.62 ± 4.59 |
| kcen | input-lanjian | 17.5 ± 0.7 | 16.5 | 20.9 | 19.63 ± 4.59 |
| kcen | input-mattcl | 17.8 ± 2.1 | 16.4 | 42.7 | 19.89 ± 5.14 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>1938800261</pre>|<pre>1112</pre>|
|input-lanjian|<pre>2075724761</pre>|<pre>1072</pre>|
|input-mattcl|<pre>1969958987</pre>|<pre>1068</pre>|
|input-pting|<pre>1584748274</pre>|<pre>1026</pre>|