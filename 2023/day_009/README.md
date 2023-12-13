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
| mattcl | input-kcen | 0.9 ± 0.2 | 0.1 | 1.2 | 1.00 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.7 | 1.03 ± 0.29 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.6 | 1.05 ± 0.29 |
| mattcl | input-pting | 0.9 ± 2.3 | 0.1 | 33.5 | 1.06 ± 2.65 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.7 | 1.6 | 1.11 ± 0.35 |
| lanjian | input-pting | 1.0 ± 0.2 | 0.7 | 1.6 | 1.12 ± 0.34 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.7 | 1.6 | 1.14 ± 0.36 |
| lanjian | input-mattcl | 1.0 ± 0.2 | 0.7 | 1.7 | 1.14 ± 0.36 |
| mattcl-ts | input-mattcl | 12.5 ± 0.4 | 11.6 | 13.6 | 14.11 ± 2.95 |
| mattcl-ts | input-pting | 12.5 ± 0.3 | 11.6 | 13.3 | 14.13 ± 2.95 |
| mattcl-ts | input-kcen | 12.5 ± 0.3 | 11.4 | 13.2 | 14.14 ± 2.95 |
| mattcl-ts | input-lanjian | 12.6 ± 0.3 | 11.7 | 13.4 | 14.17 ± 2.96 |
| mattcl-py | input-pting | 15.1 ± 0.4 | 14.1 | 18.3 | 17.07 ± 3.57 |
| mattcl-py | input-kcen | 15.2 ± 0.5 | 14.0 | 18.4 | 17.11 ± 3.59 |
| mattcl-py | input-mattcl | 15.2 ± 0.7 | 14.2 | 18.3 | 17.19 ± 3.64 |
| mattcl-py | input-lanjian | 15.2 ± 0.7 | 14.1 | 18.5 | 17.20 ± 3.65 |
| pting | input-pting | 16.2 ± 0.6 | 15.2 | 19.4 | 18.24 ± 3.84 |
| pting | input-lanjian | 16.3 ± 0.6 | 15.1 | 19.2 | 18.37 ± 3.86 |
| pting | input-kcen | 16.3 ± 0.6 | 15.1 | 18.9 | 18.40 ± 3.87 |
| pting | input-mattcl | 16.3 ± 0.6 | 15.2 | 18.8 | 18.43 ± 3.87 |
| kcen | input-kcen | 17.5 ± 0.6 | 16.5 | 21.2 | 19.80 ± 4.15 |
| kcen | input-mattcl | 17.6 ± 0.8 | 16.4 | 20.8 | 19.92 ± 4.22 |
| kcen | input-pting | 17.8 ± 4.3 | 16.3 | 67.7 | 20.11 ± 6.37 |
| kcen | input-lanjian | 18.0 ± 3.3 | 16.4 | 59.3 | 20.28 ± 5.59 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>1938800261</pre>|<pre>1112</pre>|
|input-lanjian|<pre>2075724761</pre>|<pre>1072</pre>|
|input-mattcl|<pre>1969958987</pre>|<pre>1068</pre>|
|input-pting|<pre>1584748274</pre>|<pre>1026</pre>|