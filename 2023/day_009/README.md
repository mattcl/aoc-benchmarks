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
| mattcl | input-kcen | 0.9 ± 0.2 | 0.3 | 1.5 | 1.02 ± 0.30 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.2 | 1.2 | 1.04 ± 0.30 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.5 | 1.06 ± 0.32 |
| lanjian | input-kcen | 0.9 ± 0.2 | 0.6 | 1.6 | 1.11 ± 0.36 |
| lanjian | input-mattcl | 1.0 ± 0.2 | 0.7 | 1.5 | 1.13 ± 0.36 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.7 | 1.6 | 1.13 ± 0.37 |
| lanjian | input-pting | 1.0 ± 0.2 | 0.7 | 1.7 | 1.20 ± 0.40 |
| mattcl-ts | input-pting | 12.4 ± 0.4 | 11.4 | 13.2 | 14.60 ± 3.35 |
| mattcl-ts | input-kcen | 12.5 ± 0.3 | 11.6 | 13.4 | 14.62 ± 3.35 |
| mattcl-ts | input-lanjian | 12.5 ± 0.3 | 11.6 | 13.6 | 14.65 ± 3.36 |
| mattcl-ts | input-mattcl | 12.5 ± 0.3 | 11.7 | 13.4 | 14.68 ± 3.36 |
| mattcl-py | input-kcen | 15.1 ± 0.5 | 14.0 | 18.1 | 17.71 ± 4.08 |
| mattcl-py | input-lanjian | 15.2 ± 0.6 | 14.3 | 18.4 | 17.80 ± 4.11 |
| mattcl-py | input-pting | 15.2 ± 0.7 | 14.1 | 18.2 | 17.81 ± 4.13 |
| mattcl-py | input-mattcl | 15.2 ± 0.7 | 14.3 | 18.4 | 17.88 ± 4.14 |
| pting | input-kcen | 16.2 ± 0.5 | 15.2 | 19.7 | 19.03 ± 4.37 |
| pting | input-lanjian | 16.2 ± 0.6 | 15.1 | 19.5 | 19.06 ± 4.40 |
| pting | input-mattcl | 16.4 ± 0.7 | 15.4 | 19.8 | 19.22 ± 4.46 |
| pting | input-pting | 16.5 ± 3.6 | 15.1 | 54.8 | 19.40 ± 6.08 |
| kcen | input-pting | 17.5 ± 0.7 | 16.2 | 20.4 | 20.50 ± 4.74 |
| kcen | input-kcen | 17.5 ± 0.6 | 16.5 | 20.6 | 20.55 ± 4.73 |
| kcen | input-lanjian | 17.7 ± 0.8 | 16.6 | 21.1 | 20.72 ± 4.81 |
| kcen | input-mattcl | 17.7 ± 1.9 | 16.6 | 41.2 | 20.78 ± 5.23 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>1938800261</pre>|<pre>1112</pre>|
|input-lanjian|<pre>2075724761</pre>|<pre>1072</pre>|
|input-mattcl|<pre>1969958987</pre>|<pre>1068</pre>|
|input-pting|<pre>1584748274</pre>|<pre>1026</pre>|