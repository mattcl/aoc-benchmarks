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
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.2 | 1.00 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.1 | 1.06 ± 0.32 |
| mattcl | input-pting | 1.0 ± 0.1 | 0.2 | 1.1 | 1.07 ± 0.32 |
| mattcl | input-kcen | 1.0 ± 0.1 | 0.5 | 1.6 | 1.08 ± 0.31 |
| lanjian | input-mattcl | 1.0 ± 0.2 | 0.7 | 1.7 | 1.12 ± 0.39 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.6 | 1.6 | 1.13 ± 0.39 |
| lanjian | input-pting | 1.0 ± 0.2 | 0.7 | 1.6 | 1.14 ± 0.40 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.7 | 1.7 | 1.16 ± 0.40 |
| mattcl-ts | input-kcen | 12.6 ± 0.3 | 11.4 | 13.5 | 14.10 ± 3.56 |
| mattcl-ts | input-lanjian | 12.6 ± 0.3 | 11.6 | 13.6 | 14.11 ± 3.56 |
| mattcl-ts | input-mattcl | 12.6 ± 0.3 | 11.7 | 13.9 | 14.12 ± 3.56 |
| mattcl-ts | input-pting | 12.6 ± 0.3 | 11.7 | 13.7 | 14.14 ± 3.57 |
| mattcl-py | input-kcen | 15.3 ± 0.6 | 14.5 | 18.6 | 17.16 ± 4.35 |
| mattcl-py | input-pting | 15.3 ± 0.6 | 14.1 | 17.9 | 17.17 ± 4.37 |
| mattcl-py | input-lanjian | 15.3 ± 0.7 | 14.1 | 18.4 | 17.20 ± 4.39 |
| mattcl-py | input-mattcl | 15.4 ± 0.7 | 14.1 | 19.0 | 17.26 ± 4.40 |
| pting | input-mattcl | 16.3 ± 0.6 | 15.4 | 19.3 | 18.33 ± 4.64 |
| pting | input-kcen | 16.4 ± 0.6 | 15.5 | 19.4 | 18.40 ± 4.66 |
| pting | input-lanjian | 16.4 ± 0.6 | 15.4 | 19.5 | 18.43 ± 4.67 |
| pting | input-pting | 16.6 ± 3.1 | 15.2 | 55.6 | 18.61 ± 5.80 |
| kcen | input-pting | 17.5 ± 0.7 | 16.1 | 20.9 | 19.63 ± 4.98 |
| kcen | input-lanjian | 17.8 ± 0.9 | 16.8 | 21.3 | 19.95 ± 5.10 |
| kcen | input-kcen | 17.8 ± 0.8 | 16.8 | 21.0 | 19.96 ± 5.08 |
| kcen | input-mattcl | 17.9 ± 1.8 | 16.7 | 38.5 | 20.10 ± 5.42 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>1938800261</pre>|<pre>1112</pre>|
|input-lanjian|<pre>2075724761</pre>|<pre>1072</pre>|
|input-mattcl|<pre>1969958987</pre>|<pre>1068</pre>|
|input-pting|<pre>1584748274</pre>|<pre>1026</pre>|