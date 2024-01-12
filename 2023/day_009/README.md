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
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.6 | 1.00 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.2 | 1.01 ± 0.27 |
| mattcl | input-pting | 1.0 ± 0.1 | 0.2 | 1.7 | 1.03 ± 0.26 |
| mattcl | input-lanjian | 1.0 ± 0.1 | 0.4 | 1.4 | 1.05 ± 0.26 |
| lanjian | input-pting | 1.0 ± 0.2 | 0.7 | 1.7 | 1.11 ± 0.33 |
| lanjian | input-mattcl | 1.0 ± 0.2 | 0.7 | 1.6 | 1.11 ± 0.33 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.7 | 1.8 | 1.11 ± 0.33 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.7 | 1.6 | 1.12 ± 0.35 |
| mattcl-ts | input-lanjian | 12.5 ± 0.3 | 11.6 | 13.4 | 13.28 ± 2.72 |
| mattcl-ts | input-kcen | 12.5 ± 0.3 | 11.4 | 13.5 | 13.29 ± 2.72 |
| mattcl-ts | input-mattcl | 12.5 ± 0.3 | 11.8 | 13.3 | 13.34 ± 2.73 |
| mattcl-ts | input-pting | 12.6 ± 3.2 | 11.6 | 57.6 | 13.44 ± 4.38 |
| mattcl-py | input-pting | 15.1 ± 0.6 | 14.1 | 17.9 | 16.06 ± 3.32 |
| mattcl-py | input-lanjian | 15.1 ± 0.6 | 14.1 | 18.5 | 16.09 ± 3.33 |
| mattcl-py | input-kcen | 15.2 ± 0.6 | 14.0 | 18.5 | 16.13 ± 3.34 |
| mattcl-py | input-mattcl | 15.2 ± 0.7 | 14.2 | 18.3 | 16.16 ± 3.36 |
| pting | input-lanjian | 16.2 ± 0.5 | 15.2 | 18.6 | 17.23 ± 3.55 |
| pting | input-kcen | 16.3 ± 0.7 | 15.1 | 19.6 | 17.33 ± 3.59 |
| pting | input-pting | 16.5 ± 4.1 | 14.9 | 63.1 | 17.55 ± 5.67 |
| pting | input-mattcl | 16.6 ± 2.2 | 15.2 | 41.2 | 17.65 ± 4.27 |
| kcen | input-pting | 17.3 ± 0.5 | 16.5 | 19.8 | 18.37 ± 3.77 |
| kcen | input-kcen | 17.6 ± 0.6 | 16.8 | 20.2 | 18.69 ± 3.85 |
| kcen | input-mattcl | 17.6 ± 0.7 | 16.6 | 20.7 | 18.71 ± 3.87 |
| kcen | input-lanjian | 17.6 ± 0.8 | 16.6 | 20.8 | 18.73 ± 3.90 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>1938800261</pre>|<pre>1112</pre>|
|input-lanjian|<pre>2075724761</pre>|<pre>1072</pre>|
|input-mattcl|<pre>1969958987</pre>|<pre>1068</pre>|
|input-pting|<pre>1584748274</pre>|<pre>1026</pre>|