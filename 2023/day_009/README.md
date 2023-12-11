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
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.4 | 1.00 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.1 | 1.3 | 1.00 ± 0.28 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.2 | 1.5 | 1.01 ± 0.29 |
| mattcl | input-kcen | 0.9 ± 0.1 | 0.3 | 1.4 | 1.02 ± 0.27 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.7 | 1.7 | 1.12 ± 0.36 |
| lanjian | input-mattcl | 1.0 ± 0.2 | 0.6 | 1.6 | 1.13 ± 0.36 |
| lanjian | input-pting | 1.0 ± 0.2 | 0.6 | 1.7 | 1.15 ± 0.36 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.7 | 1.6 | 1.15 ± 0.36 |
| mattcl-ts | input-kcen | 12.6 ± 0.3 | 11.9 | 13.4 | 14.28 ± 2.92 |
| mattcl-ts | input-mattcl | 12.6 ± 0.3 | 11.6 | 13.6 | 14.29 ± 2.93 |
| mattcl-ts | input-lanjian | 12.6 ± 0.3 | 11.8 | 13.5 | 14.30 ± 2.92 |
| mattcl-ts | input-pting | 12.7 ± 1.5 | 11.9 | 33.0 | 14.40 ± 3.38 |
| mattcl-py | input-lanjian | 15.2 ± 0.6 | 14.1 | 18.5 | 17.29 ± 3.58 |
| mattcl-py | input-kcen | 15.2 ± 0.6 | 14.0 | 18.7 | 17.31 ± 3.59 |
| mattcl-py | input-mattcl | 15.3 ± 0.6 | 14.1 | 18.8 | 17.43 ± 3.61 |
| mattcl-py | input-pting | 15.7 ± 3.7 | 14.3 | 65.8 | 17.81 ± 5.56 |
| pting | input-mattcl | 16.3 ± 0.6 | 14.9 | 19.3 | 18.53 ± 3.83 |
| pting | input-pting | 16.3 ± 0.6 | 15.2 | 19.5 | 18.55 ± 3.83 |
| pting | input-kcen | 16.4 ± 0.6 | 15.4 | 19.6 | 18.61 ± 3.85 |
| pting | input-lanjian | 16.4 ± 0.7 | 15.0 | 19.7 | 18.65 ± 3.88 |
| kcen | input-pting | 17.6 ± 0.6 | 16.7 | 21.0 | 20.00 ± 4.13 |
| kcen | input-mattcl | 17.6 ± 0.6 | 16.6 | 20.7 | 20.01 ± 4.13 |
| kcen | input-lanjian | 17.7 ± 0.7 | 16.3 | 20.6 | 20.10 ± 4.16 |
| kcen | input-kcen | 17.7 ± 0.7 | 16.8 | 21.0 | 20.11 ± 4.16 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>1938800261</pre>|<pre>1112</pre>|
|input-lanjian|<pre>2075724761</pre>|<pre>1072</pre>|
|input-mattcl|<pre>1969958987</pre>|<pre>1068</pre>|
|input-pting|<pre>1584748274</pre>|<pre>1026</pre>|