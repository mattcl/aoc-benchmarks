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
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.1 | 1.00 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.2 | 1.00 ± 0.29 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.3 | 1.01 ± 0.29 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.2 | 1.1 | 1.02 ± 0.28 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.7 | 1.6 | 1.11 ± 0.33 |
| lanjian | input-mattcl | 1.0 ± 0.2 | 0.7 | 1.6 | 1.12 ± 0.35 |
| lanjian | input-pting | 1.0 ± 0.2 | 0.7 | 1.6 | 1.13 ± 0.34 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.7 | 1.5 | 1.14 ± 0.34 |
| mattcl-ts | input-pting | 12.2 ± 0.4 | 11.1 | 13.1 | 13.64 ± 2.90 |
| mattcl-ts | input-mattcl | 12.3 ± 0.4 | 11.2 | 13.3 | 13.75 ± 2.93 |
| mattcl-ts | input-lanjian | 12.3 ± 0.4 | 11.1 | 13.1 | 13.77 ± 2.93 |
| mattcl-ts | input-kcen | 12.3 ± 0.4 | 11.3 | 13.4 | 13.78 ± 2.93 |
| mattcl-py | input-pting | 15.2 ± 0.6 | 14.2 | 18.2 | 17.06 ± 3.65 |
| mattcl-py | input-kcen | 15.2 ± 0.7 | 14.2 | 19.0 | 17.07 ± 3.67 |
| mattcl-py | input-mattcl | 15.2 ± 0.7 | 14.2 | 18.9 | 17.10 ± 3.68 |
| mattcl-py | input-lanjian | 15.5 ± 4.1 | 14.2 | 71.8 | 17.34 ± 5.88 |
| pting | input-lanjian | 16.2 ± 0.6 | 15.1 | 18.9 | 18.16 ± 3.88 |
| pting | input-kcen | 16.2 ± 0.6 | 15.0 | 18.5 | 18.20 ± 3.88 |
| pting | input-pting | 16.5 ± 4.5 | 15.0 | 75.8 | 18.49 ± 6.36 |
| pting | input-mattcl | 16.8 ± 5.2 | 15.1 | 69.7 | 18.86 ± 7.08 |
| kcen | input-pting | 17.4 ± 0.7 | 16.3 | 20.4 | 19.47 ± 4.17 |
| kcen | input-lanjian | 17.5 ± 0.6 | 16.6 | 20.6 | 19.63 ± 4.19 |
| kcen | input-mattcl | 17.5 ± 0.6 | 16.5 | 20.8 | 19.65 ± 4.18 |
| kcen | input-kcen | 17.6 ± 0.7 | 16.5 | 20.5 | 19.69 ± 4.20 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>1938800261</pre>|<pre>1112</pre>|
|input-lanjian|<pre>2075724761</pre>|<pre>1072</pre>|
|input-mattcl|<pre>1969958987</pre>|<pre>1068</pre>|
|input-pting|<pre>1584748274</pre>|<pre>1026</pre>|