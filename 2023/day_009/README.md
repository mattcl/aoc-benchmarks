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
| mattcl | input-kcen | 1.0 ± 0.2 | 0.2 | 1.6 | 1.01 ± 0.24 |
| mattcl | input-mattcl | 1.0 ± 0.1 | 0.6 | 1.6 | 1.03 ± 0.24 |
| mattcl | input-pting | 1.0 ± 0.2 | 0.2 | 1.5 | 1.05 ± 0.26 |
| lanjian | input-pting | 1.0 ± 0.3 | 0.7 | 1.7 | 1.10 ± 0.34 |
| lanjian | input-mattcl | 1.0 ± 0.2 | 0.7 | 1.7 | 1.11 ± 0.32 |
| lanjian | input-kcen | 1.1 ± 0.3 | 0.7 | 1.7 | 1.11 ± 0.34 |
| lanjian | input-lanjian | 1.2 ± 2.4 | 0.7 | 35.4 | 1.26 ± 2.59 |
| mattcl-ts | input-pting | 12.5 ± 0.3 | 11.6 | 13.3 | 13.24 ± 2.38 |
| mattcl-ts | input-lanjian | 12.6 ± 0.3 | 11.3 | 13.9 | 13.29 ± 2.39 |
| mattcl-ts | input-mattcl | 12.6 ± 0.3 | 11.6 | 13.9 | 13.33 ± 2.40 |
| mattcl-ts | input-kcen | 12.9 ± 4.9 | 11.7 | 81.1 | 13.65 ± 5.68 |
| mattcl-py | input-kcen | 15.4 ± 0.7 | 14.4 | 18.6 | 16.26 ± 2.98 |
| mattcl-py | input-lanjian | 15.4 ± 0.6 | 14.1 | 18.8 | 16.30 ± 2.98 |
| mattcl-py | input-mattcl | 15.4 ± 0.6 | 14.2 | 18.6 | 16.30 ± 2.98 |
| mattcl-py | input-pting | 15.4 ± 0.7 | 14.3 | 18.6 | 16.31 ± 3.00 |
| pting | input-kcen | 16.4 ± 0.6 | 15.1 | 19.4 | 17.27 ± 3.13 |
| pting | input-lanjian | 16.4 ± 0.6 | 15.4 | 18.9 | 17.30 ± 3.15 |
| pting | input-pting | 16.4 ± 0.7 | 15.1 | 19.3 | 17.30 ± 3.16 |
| pting | input-mattcl | 16.4 ± 0.6 | 15.4 | 19.4 | 17.31 ± 3.15 |
| kcen | input-pting | 17.5 ± 0.7 | 16.7 | 20.9 | 18.53 ± 3.37 |
| kcen | input-mattcl | 17.6 ± 0.6 | 16.9 | 20.9 | 18.62 ± 3.38 |
| kcen | input-lanjian | 17.7 ± 0.7 | 16.8 | 20.8 | 18.74 ± 3.41 |
| kcen | input-kcen | 17.9 ± 0.7 | 16.9 | 21.1 | 18.95 ± 3.47 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>1938800261</pre>|<pre>1112</pre>|
|input-lanjian|<pre>2075724761</pre>|<pre>1072</pre>|
|input-mattcl|<pre>1969958987</pre>|<pre>1068</pre>|
|input-pting|<pre>1584748274</pre>|<pre>1026</pre>|