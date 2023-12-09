# Day 6 benchmarks

[link to problem](https://adventofcode.com/2023/day/6)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 6)

- [kcen](https://github.com/kcen/aoc2023) (python)
- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [mattcl-ts](https://github.com/mattcl/aoc2023-js) (typescript (bun))
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| lanjian | input-mattcl | 0.6 ± 0.2 | 0.1 | 1.0 | 1.00 |
| mattcl | input-kcen | 0.7 ± 0.2 | 0.1 | 1.2 | 1.25 ± 0.63 |
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.0 | 1.28 ± 0.61 |
| lanjian | input-pting | 0.8 ± 0.2 | 0.1 | 1.0 | 1.28 ± 0.60 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.2 | 1.29 ± 0.61 |
| lanjian | input-lanjian | 0.8 ± 0.2 | 0.2 | 1.5 | 1.32 ± 0.60 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.1 | 1.1 | 1.32 ± 0.61 |
| lanjian | input-kcen | 0.8 ± 0.1 | 0.2 | 1.1 | 1.35 ± 0.60 |
| mattcl-ts | input-kcen | 9.6 ± 0.4 | 8.6 | 10.5 | 16.12 ± 6.65 |
| mattcl-ts | input-lanjian | 9.6 ± 0.3 | 8.6 | 10.5 | 16.12 ± 6.65 |
| mattcl-ts | input-pting | 9.6 ± 0.4 | 8.7 | 10.4 | 16.13 ± 6.66 |
| mattcl-ts | input-mattcl | 9.6 ± 0.4 | 8.6 | 10.4 | 16.19 ± 6.68 |
| mattcl-py | input-mattcl | 14.1 ± 0.6 | 12.9 | 17.8 | 23.65 ± 9.77 |
| mattcl-py | input-kcen | 14.1 ± 0.6 | 12.8 | 18.1 | 23.67 ± 9.78 |
| pting | input-lanjian | 14.1 ± 0.5 | 13.1 | 17.1 | 23.70 ± 9.78 |
| kcen | input-lanjian | 14.1 ± 0.6 | 13.2 | 17.9 | 23.71 ± 9.80 |
| pting | input-kcen | 14.1 ± 0.6 | 13.0 | 17.7 | 23.74 ± 9.82 |
| kcen | input-pting | 14.1 ± 0.6 | 13.1 | 17.1 | 23.75 ± 9.81 |
| mattcl-py | input-lanjian | 14.2 ± 0.6 | 13.0 | 17.3 | 23.79 ± 9.84 |
| pting | input-pting | 14.2 ± 0.6 | 13.0 | 17.3 | 23.81 ± 9.84 |
| mattcl-py | input-pting | 14.2 ± 0.7 | 13.1 | 17.8 | 23.88 ± 9.89 |
| pting | input-mattcl | 14.2 ± 0.6 | 13.2 | 17.2 | 23.92 ± 9.88 |
| kcen | input-mattcl | 14.3 ± 2.3 | 13.1 | 44.5 | 24.10 ± 10.64 |
| kcen | input-kcen | 14.4 ± 2.6 | 13.2 | 49.8 | 24.18 ± 10.84 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|