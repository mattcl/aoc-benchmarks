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
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.2 | 1.00 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.2 | 1.3 | 1.03 ± 0.31 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.1 | 1.1 | 1.04 ± 0.30 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.4 | 1.2 | 1.05 ± 0.29 |
| lanjian | input-mattcl | 1.0 ± 0.2 | 0.7 | 1.6 | 1.13 ± 0.35 |
| lanjian | input-lanjian | 1.0 ± 0.3 | 0.7 | 1.7 | 1.13 ± 0.38 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.7 | 1.6 | 1.17 ± 0.37 |
| lanjian | input-pting | 1.0 ± 0.3 | 0.7 | 1.7 | 1.17 ± 0.38 |
| mattcl-ts | input-pting | 12.6 ± 0.3 | 11.6 | 13.6 | 14.13 ± 3.14 |
| mattcl-ts | input-mattcl | 12.6 ± 0.3 | 11.6 | 13.4 | 14.16 ± 3.14 |
| mattcl-ts | input-kcen | 12.7 ± 0.4 | 11.8 | 14.5 | 14.21 ± 3.16 |
| mattcl-ts | input-lanjian | 12.7 ± 1.8 | 11.3 | 37.6 | 14.25 ± 3.73 |
| mattcl-py | input-mattcl | 15.3 ± 0.5 | 14.2 | 18.6 | 17.20 ± 3.84 |
| mattcl-py | input-pting | 15.4 ± 0.5 | 14.3 | 18.0 | 17.23 ± 3.84 |
| mattcl-py | input-kcen | 15.4 ± 0.7 | 14.1 | 18.6 | 17.28 ± 3.89 |
| mattcl-py | input-lanjian | 15.7 ± 3.9 | 13.9 | 54.7 | 17.66 ± 5.90 |
| pting | input-pting | 16.3 ± 0.7 | 15.0 | 19.2 | 18.29 ± 4.10 |
| pting | input-kcen | 16.5 ± 0.7 | 15.4 | 19.4 | 18.48 ± 4.14 |
| pting | input-lanjian | 16.5 ± 0.8 | 15.1 | 19.8 | 18.50 ± 4.17 |
| pting | input-mattcl | 16.5 ± 0.6 | 15.3 | 20.2 | 18.50 ± 4.14 |
| kcen | input-pting | 17.6 ± 0.7 | 16.5 | 21.0 | 19.72 ± 4.42 |
| kcen | input-kcen | 17.6 ± 0.6 | 16.9 | 20.8 | 19.77 ± 4.41 |
| kcen | input-mattcl | 17.7 ± 0.7 | 16.7 | 20.8 | 19.87 ± 4.44 |
| kcen | input-lanjian | 17.7 ± 0.7 | 16.9 | 20.7 | 19.88 ± 4.45 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>1938800261</pre>|<pre>1112</pre>|
|input-lanjian|<pre>2075724761</pre>|<pre>1072</pre>|
|input-mattcl|<pre>1969958987</pre>|<pre>1068</pre>|
|input-pting|<pre>1584748274</pre>|<pre>1026</pre>|