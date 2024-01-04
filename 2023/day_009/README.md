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
| mattcl | input-pting | 0.7 ± 0.3 | 0.2 | 1.7 | 1.00 |
| mattcl | input-mattcl | 1.0 ± 0.2 | 0.3 | 1.6 | 1.41 ± 0.67 |
| mattcl | input-lanjian | 1.1 ± 0.2 | 0.3 | 1.8 | 1.42 ± 0.67 |
| mattcl | input-kcen | 1.1 ± 0.2 | 0.5 | 1.8 | 1.43 ± 0.68 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.7 | 1.8 | 1.47 ± 0.73 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.8 | 1.8 | 1.48 ± 0.74 |
| lanjian | input-pting | 1.1 ± 0.3 | 0.8 | 3.8 | 1.52 ± 0.81 |
| lanjian | input-lanjian | 1.3 ± 2.9 | 0.7 | 42.1 | 1.77 ± 4.00 |
| mattcl-ts | input-mattcl | 12.6 ± 0.4 | 11.6 | 13.6 | 17.02 ± 7.61 |
| mattcl-ts | input-pting | 12.7 ± 0.3 | 11.8 | 13.6 | 17.05 ± 7.62 |
| mattcl-ts | input-kcen | 12.7 ± 0.3 | 11.8 | 13.5 | 17.14 ± 7.66 |
| mattcl-ts | input-lanjian | 12.7 ± 0.3 | 11.8 | 14.1 | 17.15 ± 7.67 |
| mattcl-py | input-pting | 15.5 ± 0.6 | 14.3 | 18.1 | 20.85 ± 9.34 |
| mattcl-py | input-kcen | 15.5 ± 0.7 | 14.4 | 18.3 | 20.89 ± 9.37 |
| mattcl-py | input-mattcl | 15.5 ± 0.6 | 14.5 | 18.6 | 20.93 ± 9.38 |
| mattcl-py | input-lanjian | 15.6 ± 2.2 | 14.2 | 44.6 | 21.05 ± 9.87 |
| pting | input-mattcl | 16.4 ± 0.5 | 15.6 | 20.1 | 22.13 ± 9.91 |
| pting | input-pting | 16.5 ± 0.7 | 15.3 | 20.0 | 22.21 ± 9.97 |
| pting | input-lanjian | 16.5 ± 0.5 | 15.3 | 19.1 | 22.22 ± 9.95 |
| pting | input-kcen | 16.7 ± 1.4 | 15.3 | 34.0 | 22.45 ± 10.20 |
| kcen | input-pting | 17.7 ± 0.8 | 16.7 | 20.6 | 23.89 ± 10.72 |
| kcen | input-lanjian | 17.9 ± 0.7 | 16.9 | 21.0 | 24.07 ± 10.79 |
| kcen | input-mattcl | 17.9 ± 0.8 | 17.0 | 21.4 | 24.15 ± 10.84 |
| kcen | input-kcen | 18.0 ± 1.1 | 17.0 | 29.2 | 24.23 ± 10.93 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>1938800261</pre>|<pre>1112</pre>|
|input-lanjian|<pre>2075724761</pre>|<pre>1072</pre>|
|input-mattcl|<pre>1969958987</pre>|<pre>1068</pre>|
|input-pting|<pre>1584748274</pre>|<pre>1026</pre>|