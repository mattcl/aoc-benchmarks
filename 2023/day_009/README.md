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
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.1 | 1.2 | 1.00 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.2 | 1.5 | 1.02 ± 0.34 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.1 | 1.4 | 1.03 ± 0.33 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.1 | 1.04 ± 0.31 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.7 | 1.6 | 1.13 ± 0.38 |
| lanjian | input-mattcl | 1.0 ± 0.2 | 0.7 | 1.6 | 1.14 ± 0.39 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.6 | 1.7 | 1.15 ± 0.40 |
| lanjian | input-pting | 1.0 ± 0.2 | 0.7 | 1.6 | 1.16 ± 0.38 |
| mattcl-ts | input-pting | 12.5 ± 0.3 | 11.5 | 13.5 | 14.40 ± 3.51 |
| mattcl-ts | input-lanjian | 12.5 ± 0.3 | 11.5 | 13.4 | 14.41 ± 3.51 |
| mattcl-ts | input-mattcl | 12.5 ± 0.4 | 11.2 | 13.7 | 14.43 ± 3.52 |
| mattcl-ts | input-kcen | 12.7 ± 3.5 | 11.6 | 61.8 | 14.74 ± 5.39 |
| mattcl-py | input-mattcl | 15.1 ± 0.5 | 14.2 | 17.6 | 17.48 ± 4.28 |
| mattcl-py | input-lanjian | 15.2 ± 0.7 | 14.1 | 18.2 | 17.56 ± 4.34 |
| mattcl-py | input-pting | 15.2 ± 0.7 | 14.1 | 18.2 | 17.57 ± 4.33 |
| mattcl-py | input-kcen | 15.6 ± 4.5 | 14.2 | 70.0 | 18.06 ± 6.82 |
| pting | input-pting | 16.1 ± 0.7 | 15.0 | 19.0 | 18.60 ± 4.57 |
| pting | input-lanjian | 16.2 ± 0.7 | 14.9 | 18.6 | 18.78 ± 4.61 |
| pting | input-mattcl | 16.3 ± 0.7 | 15.4 | 19.1 | 18.86 ± 4.64 |
| pting | input-kcen | 16.4 ± 2.3 | 15.2 | 46.7 | 18.99 ± 5.34 |
| kcen | input-pting | 17.4 ± 0.7 | 16.3 | 20.7 | 20.06 ± 4.92 |
| kcen | input-lanjian | 17.5 ± 0.6 | 16.2 | 20.5 | 20.19 ± 4.93 |
| kcen | input-kcen | 17.5 ± 0.5 | 16.6 | 20.3 | 20.20 ± 4.93 |
| kcen | input-mattcl | 17.5 ± 0.7 | 16.3 | 20.8 | 20.26 ± 4.98 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>1938800261</pre>|<pre>1112</pre>|
|input-lanjian|<pre>2075724761</pre>|<pre>1072</pre>|
|input-mattcl|<pre>1969958987</pre>|<pre>1068</pre>|
|input-pting|<pre>1584748274</pre>|<pre>1026</pre>|