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
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.1 | 1.3 | 1.00 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.2 | 1.8 | 1.04 ± 0.31 |
| mattcl | input-mattcl | 0.9 ± 0.1 | 0.4 | 1.6 | 1.07 ± 0.29 |
| mattcl | input-kcen | 0.9 ± 0.1 | 0.4 | 1.4 | 1.07 ± 0.29 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.6 | 1.6 | 1.11 ± 0.37 |
| lanjian | input-mattcl | 1.0 ± 0.2 | 0.6 | 1.5 | 1.11 ± 0.36 |
| lanjian | input-pting | 1.0 ± 0.3 | 0.6 | 1.7 | 1.12 ± 0.39 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.6 | 1.6 | 1.13 ± 0.38 |
| mattcl-ts | input-pting | 12.3 ± 0.4 | 11.2 | 13.2 | 14.23 ± 3.27 |
| mattcl-ts | input-kcen | 12.4 ± 0.4 | 11.2 | 13.2 | 14.34 ± 3.29 |
| mattcl-ts | input-mattcl | 12.4 ± 0.3 | 11.7 | 13.5 | 14.34 ± 3.29 |
| mattcl-ts | input-lanjian | 12.6 ± 2.7 | 11.1 | 50.8 | 14.50 ± 4.58 |
| mattcl-py | input-mattcl | 15.3 ± 0.6 | 14.5 | 18.3 | 17.61 ± 4.07 |
| mattcl-py | input-lanjian | 15.3 ± 0.5 | 14.3 | 18.1 | 17.63 ± 4.07 |
| mattcl-py | input-pting | 15.3 ± 0.6 | 14.3 | 18.0 | 17.65 ± 4.08 |
| mattcl-py | input-kcen | 15.5 ± 2.7 | 14.4 | 51.9 | 17.89 ± 5.13 |
| pting | input-pting | 16.4 ± 0.8 | 14.9 | 19.6 | 18.93 ± 4.41 |
| pting | input-kcen | 16.4 ± 0.7 | 15.2 | 19.4 | 18.95 ± 4.39 |
| pting | input-mattcl | 16.4 ± 0.8 | 15.5 | 19.8 | 18.97 ± 4.42 |
| pting | input-lanjian | 16.9 ± 5.3 | 15.2 | 72.4 | 19.53 ± 7.60 |
| kcen | input-pting | 17.5 ± 0.7 | 16.5 | 20.7 | 20.23 ± 4.68 |
| kcen | input-lanjian | 17.7 ± 0.7 | 16.6 | 21.1 | 20.38 ± 4.71 |
| kcen | input-mattcl | 17.7 ± 0.6 | 16.8 | 20.8 | 20.43 ± 4.71 |
| kcen | input-kcen | 17.8 ± 0.7 | 16.9 | 22.0 | 20.52 ± 4.75 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>1938800261</pre>|<pre>1112</pre>|
|input-lanjian|<pre>2075724761</pre>|<pre>1072</pre>|
|input-mattcl|<pre>1969958987</pre>|<pre>1068</pre>|
|input-pting|<pre>1584748274</pre>|<pre>1026</pre>|