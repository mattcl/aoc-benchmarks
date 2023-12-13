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
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.3 | 1.5 | 1.00 |
| mattcl | input-kcen | 1.0 ± 0.2 | 0.3 | 1.4 | 1.02 ± 0.26 |
| mattcl | input-pting | 1.0 ± 0.1 | 0.3 | 1.2 | 1.04 ± 0.24 |
| mattcl | input-mattcl | 1.0 ± 0.1 | 0.4 | 1.3 | 1.05 ± 0.25 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.7 | 2.0 | 1.12 ± 0.32 |
| lanjian | input-mattcl | 1.1 ± 0.3 | 0.7 | 1.7 | 1.15 ± 0.35 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.7 | 1.6 | 1.16 ± 0.34 |
| lanjian | input-pting | 1.4 ± 5.2 | 0.7 | 74.7 | 1.54 ± 5.57 |
| mattcl-ts | input-lanjian | 12.5 ± 0.4 | 11.5 | 13.7 | 13.38 ± 2.59 |
| mattcl-ts | input-mattcl | 12.6 ± 0.3 | 11.7 | 13.7 | 13.42 ± 2.59 |
| mattcl-ts | input-pting | 12.6 ± 0.4 | 11.3 | 13.2 | 13.42 ± 2.60 |
| mattcl-ts | input-kcen | 12.6 ± 0.3 | 11.5 | 13.5 | 13.44 ± 2.60 |
| mattcl-py | input-mattcl | 15.2 ± 0.6 | 14.1 | 18.3 | 16.25 ± 3.17 |
| mattcl-py | input-kcen | 15.2 ± 0.6 | 14.2 | 18.3 | 16.26 ± 3.18 |
| mattcl-py | input-lanjian | 15.3 ± 0.6 | 14.3 | 18.5 | 16.30 ± 3.18 |
| mattcl-py | input-pting | 15.3 ± 0.6 | 14.1 | 18.3 | 16.31 ± 3.19 |
| pting | input-pting | 16.2 ± 0.6 | 15.2 | 19.3 | 17.29 ± 3.36 |
| pting | input-kcen | 16.3 ± 0.5 | 15.2 | 19.4 | 17.37 ± 3.37 |
| pting | input-lanjian | 16.3 ± 0.4 | 15.4 | 19.0 | 17.38 ± 3.36 |
| pting | input-mattcl | 16.4 ± 0.6 | 15.2 | 19.0 | 17.47 ± 3.40 |
| kcen | input-pting | 17.4 ± 0.6 | 16.2 | 20.3 | 18.55 ± 3.60 |
| kcen | input-lanjian | 17.6 ± 0.6 | 16.5 | 20.9 | 18.74 ± 3.65 |
| kcen | input-mattcl | 17.6 ± 0.7 | 16.7 | 20.9 | 18.79 ± 3.67 |
| kcen | input-kcen | 17.7 ± 0.7 | 16.6 | 20.9 | 18.86 ± 3.69 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>1938800261</pre>|<pre>1112</pre>|
|input-lanjian|<pre>2075724761</pre>|<pre>1072</pre>|
|input-mattcl|<pre>1969958987</pre>|<pre>1068</pre>|
|input-pting|<pre>1584748274</pre>|<pre>1026</pre>|