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
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.2 | 1.00 ± 0.26 |
| mattcl | input-pting | 0.9 ± 0.1 | 0.2 | 1.1 | 1.02 ± 0.24 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.4 | 1.6 | 1.04 ± 0.26 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.7 | 1.7 | 1.07 ± 0.33 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.6 | 1.6 | 1.09 ± 0.33 |
| lanjian | input-pting | 1.0 ± 0.2 | 0.6 | 1.6 | 1.10 ± 0.33 |
| lanjian | input-mattcl | 1.0 ± 0.3 | 0.6 | 1.6 | 1.12 ± 0.35 |
| mattcl-ts | input-pting | 12.5 ± 0.3 | 11.5 | 13.2 | 13.81 ± 2.54 |
| mattcl-ts | input-kcen | 12.6 ± 0.3 | 11.8 | 13.3 | 13.91 ± 2.55 |
| mattcl-ts | input-mattcl | 12.6 ± 0.3 | 11.8 | 13.6 | 13.91 ± 2.55 |
| mattcl-ts | input-lanjian | 12.8 ± 3.2 | 11.7 | 57.4 | 14.15 ± 4.36 |
| mattcl-py | input-pting | 15.2 ± 0.5 | 14.5 | 17.9 | 16.84 ± 3.11 |
| mattcl-py | input-mattcl | 15.3 ± 0.5 | 14.3 | 18.4 | 16.90 ± 3.12 |
| mattcl-py | input-lanjian | 15.5 ± 2.3 | 14.4 | 46.3 | 17.16 ± 4.03 |
| mattcl-py | input-kcen | 15.7 ± 3.4 | 14.0 | 47.7 | 17.40 ± 4.89 |
| pting | input-pting | 16.3 ± 0.6 | 15.3 | 19.6 | 17.98 ± 3.33 |
| pting | input-mattcl | 16.3 ± 0.6 | 15.1 | 20.0 | 18.02 ± 3.34 |
| pting | input-kcen | 16.4 ± 0.7 | 15.5 | 19.5 | 18.14 ± 3.37 |
| pting | input-lanjian | 16.5 ± 0.8 | 15.2 | 21.2 | 18.28 ± 3.42 |
| kcen | input-pting | 17.5 ± 0.7 | 16.2 | 20.2 | 19.35 ± 3.60 |
| kcen | input-mattcl | 17.7 ± 0.7 | 16.4 | 20.7 | 19.61 ± 3.65 |
| kcen | input-kcen | 17.8 ± 0.7 | 16.7 | 21.1 | 19.66 ± 3.66 |
| kcen | input-lanjian | 18.1 ± 3.0 | 16.6 | 55.8 | 19.96 ± 4.90 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>1938800261</pre>|<pre>1112</pre>|
|input-lanjian|<pre>2075724761</pre>|<pre>1072</pre>|
|input-mattcl|<pre>1969958987</pre>|<pre>1068</pre>|
|input-pting|<pre>1584748274</pre>|<pre>1026</pre>|