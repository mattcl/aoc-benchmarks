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
| lanjian | input-pting | 0.7 ± 0.2 | 0.1 | 1.3 | 1.00 |
| mattcl | input-lanjian | 0.7 ± 0.2 | 0.1 | 1.0 | 1.02 ± 0.42 |
| lanjian | input-kcen | 0.7 ± 0.2 | 0.2 | 0.9 | 1.02 ± 0.40 |
| mattcl | input-pting | 0.7 ± 0.2 | 0.1 | 1.0 | 1.05 ± 0.42 |
| lanjian | input-mattcl | 0.8 ± 0.1 | 0.2 | 1.0 | 1.07 ± 0.39 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.1 | 1.0 | 1.07 ± 0.41 |
| lanjian | input-lanjian | 0.8 ± 0.1 | 0.1 | 1.0 | 1.08 ± 0.39 |
| mattcl | input-mattcl | 0.8 ± 0.1 | 0.1 | 1.3 | 1.10 ± 0.40 |
| mattcl-ts | input-lanjian | 9.4 ± 0.4 | 8.4 | 10.5 | 13.26 ± 4.14 |
| mattcl-ts | input-mattcl | 9.4 ± 0.3 | 8.5 | 10.2 | 13.26 ± 4.13 |
| mattcl-ts | input-kcen | 9.4 ± 0.3 | 8.3 | 10.1 | 13.29 ± 4.14 |
| mattcl-ts | input-pting | 9.7 ± 2.6 | 8.3 | 46.4 | 13.66 ± 5.63 |
| mattcl-py | input-lanjian | 13.9 ± 0.5 | 12.9 | 17.1 | 19.64 ± 6.11 |
| mattcl-py | input-kcen | 13.9 ± 0.5 | 12.9 | 16.9 | 19.65 ± 6.11 |
| mattcl-py | input-pting | 13.9 ± 0.5 | 13.0 | 17.0 | 19.65 ± 6.12 |
| pting | input-mattcl | 13.9 ± 0.5 | 12.9 | 17.3 | 19.65 ± 6.12 |
| pting | input-lanjian | 13.9 ± 0.5 | 13.1 | 17.9 | 19.65 ± 6.11 |
| kcen | input-kcen | 13.9 ± 0.5 | 13.1 | 17.1 | 19.66 ± 6.12 |
| mattcl-py | input-mattcl | 14.0 ± 0.6 | 13.0 | 17.2 | 19.70 ± 6.14 |
| kcen | input-mattcl | 14.0 ± 0.5 | 13.0 | 17.1 | 19.71 ± 6.14 |
| pting | input-kcen | 14.0 ± 0.5 | 13.2 | 17.0 | 19.73 ± 6.14 |
| kcen | input-lanjian | 14.0 ± 0.5 | 13.3 | 17.2 | 19.74 ± 6.15 |
| kcen | input-pting | 14.0 ± 0.6 | 13.0 | 17.2 | 19.75 ± 6.17 |
| pting | input-pting | 14.0 ± 2.3 | 12.7 | 45.4 | 19.77 ± 6.91 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|