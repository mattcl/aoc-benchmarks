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
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.2 | 1.4 | 1.00 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.1 | 1.05 ± 0.35 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.1 | 1.1 | 1.05 ± 0.34 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.5 | 1.09 ± 0.34 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.7 | 1.5 | 1.15 ± 0.37 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.7 | 1.6 | 1.20 ± 0.40 |
| lanjian | input-mattcl | 1.0 ± 0.2 | 0.7 | 1.6 | 1.22 ± 0.41 |
| lanjian | input-pting | 1.0 ± 0.2 | 0.7 | 1.7 | 1.23 ± 0.42 |
| mattcl-ts | input-pting | 11.9 ± 0.4 | 10.8 | 13.0 | 14.27 ± 3.58 |
| mattcl-ts | input-lanjian | 12.0 ± 0.4 | 11.0 | 12.7 | 14.32 ± 3.59 |
| mattcl-ts | input-kcen | 12.0 ± 0.4 | 11.2 | 12.8 | 14.40 ± 3.61 |
| mattcl-ts | input-mattcl | 12.7 ± 6.0 | 10.9 | 69.4 | 15.16 ± 8.05 |
| mattcl-py | input-lanjian | 15.1 ± 0.5 | 14.1 | 17.7 | 18.05 ± 4.53 |
| mattcl-py | input-pting | 15.2 ± 0.6 | 14.2 | 18.3 | 18.17 ± 4.58 |
| mattcl-py | input-kcen | 15.3 ± 2.4 | 14.3 | 47.2 | 18.28 ± 5.35 |
| mattcl-py | input-mattcl | 15.3 ± 2.1 | 14.1 | 42.5 | 18.34 ± 5.18 |
| pting | input-pting | 16.1 ± 0.6 | 15.0 | 18.9 | 19.29 ± 4.86 |
| pting | input-lanjian | 16.2 ± 0.6 | 15.1 | 19.4 | 19.33 ± 4.86 |
| pting | input-kcen | 16.3 ± 0.7 | 15.0 | 19.2 | 19.43 ± 4.90 |
| pting | input-mattcl | 16.4 ± 0.7 | 15.1 | 19.1 | 19.54 ± 4.93 |
| kcen | input-pting | 17.5 ± 0.8 | 16.4 | 20.7 | 20.89 ± 5.28 |
| kcen | input-kcen | 17.5 ± 0.6 | 16.4 | 20.2 | 20.96 ± 5.26 |
| kcen | input-mattcl | 17.6 ± 0.7 | 16.8 | 21.1 | 20.99 ± 5.30 |
| kcen | input-lanjian | 17.6 ± 0.7 | 16.8 | 21.0 | 21.01 ± 5.29 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>1938800261</pre>|<pre>1112</pre>|
|input-lanjian|<pre>2075724761</pre>|<pre>1072</pre>|
|input-mattcl|<pre>1969958987</pre>|<pre>1068</pre>|
|input-pting|<pre>1584748274</pre>|<pre>1026</pre>|