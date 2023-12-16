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
| mattcl | input-pting | 0.9 ± 0.2 | 0.2 | 1.5 | 1.01 ± 0.24 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.4 | 1.6 | 1.03 ± 0.23 |
| mattcl | input-kcen | 1.0 ± 0.1 | 0.4 | 1.6 | 1.05 ± 0.22 |
| lanjian | input-mattcl | 1.0 ± 0.2 | 0.7 | 1.7 | 1.08 ± 0.30 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.7 | 1.6 | 1.10 ± 0.32 |
| lanjian | input-pting | 1.0 ± 0.2 | 0.7 | 1.7 | 1.11 ± 0.31 |
| lanjian | input-lanjian | 1.0 ± 0.3 | 0.7 | 1.7 | 1.11 ± 0.33 |
| mattcl-ts | input-mattcl | 12.6 ± 0.3 | 11.7 | 13.6 | 13.61 ± 2.25 |
| mattcl-ts | input-pting | 12.6 ± 0.4 | 11.3 | 13.7 | 13.62 ± 2.25 |
| mattcl-ts | input-lanjian | 12.6 ± 0.3 | 11.5 | 14.0 | 13.62 ± 2.25 |
| mattcl-ts | input-kcen | 12.6 ± 0.4 | 11.5 | 13.9 | 13.66 ± 2.26 |
| mattcl-py | input-mattcl | 15.4 ± 0.6 | 14.2 | 18.5 | 16.66 ± 2.80 |
| mattcl-py | input-pting | 15.5 ± 0.6 | 14.7 | 18.3 | 16.72 ± 2.80 |
| mattcl-py | input-lanjian | 15.5 ± 0.7 | 14.5 | 18.9 | 16.74 ± 2.83 |
| mattcl-py | input-kcen | 15.6 ± 0.8 | 14.0 | 19.2 | 16.85 ± 2.88 |
| pting | input-pting | 16.4 ± 0.6 | 15.7 | 19.6 | 17.75 ± 2.97 |
| pting | input-lanjian | 16.5 ± 0.6 | 15.1 | 19.7 | 17.79 ± 2.97 |
| pting | input-mattcl | 16.5 ± 0.6 | 15.2 | 19.4 | 17.82 ± 2.99 |
| pting | input-kcen | 16.7 ± 0.7 | 15.4 | 19.7 | 18.01 ± 3.02 |
| kcen | input-pting | 17.9 ± 0.8 | 16.8 | 21.3 | 19.34 ± 3.28 |
| kcen | input-lanjian | 18.1 ± 0.7 | 17.2 | 21.9 | 19.59 ± 3.29 |
| kcen | input-mattcl | 18.2 ± 0.8 | 16.9 | 21.3 | 19.63 ± 3.31 |
| kcen | input-kcen | 19.0 ± 5.8 | 17.0 | 67.3 | 20.55 ± 7.15 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>1938800261</pre>|<pre>1112</pre>|
|input-lanjian|<pre>2075724761</pre>|<pre>1072</pre>|
|input-mattcl|<pre>1969958987</pre>|<pre>1068</pre>|
|input-pting|<pre>1584748274</pre>|<pre>1026</pre>|