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
| lanjian | input-mattcl | 0.7 ± 0.2 | 0.1 | 1.0 | 1.00 |
| lanjian | input-pting | 0.7 ± 0.2 | 0.1 | 1.0 | 1.02 ± 0.39 |
| lanjian | input-kcen | 0.7 ± 0.2 | 0.1 | 1.2 | 1.02 ± 0.40 |
| lanjian | input-lanjian | 0.7 ± 0.2 | 0.1 | 1.0 | 1.02 ± 0.39 |
| mattcl | input-mattcl | 0.7 ± 0.2 | 0.1 | 0.9 | 1.04 ± 0.41 |
| mattcl | input-kcen | 0.7 ± 0.2 | 0.1 | 1.0 | 1.06 ± 0.39 |
| mattcl | input-lanjian | 0.7 ± 0.2 | 0.0 | 1.2 | 1.07 ± 0.40 |
| mattcl | input-pting | 0.8 ± 0.1 | 0.3 | 1.0 | 1.13 ± 0.37 |
| mattcl-ts | input-mattcl | 9.4 ± 0.4 | 8.5 | 10.3 | 13.72 ± 3.96 |
| mattcl-ts | input-lanjian | 9.5 ± 0.3 | 8.5 | 10.3 | 13.76 ± 3.97 |
| mattcl-ts | input-pting | 9.5 ± 0.4 | 8.4 | 10.8 | 13.77 ± 3.99 |
| mattcl-ts | input-kcen | 9.7 ± 2.1 | 8.6 | 38.1 | 14.11 ± 5.02 |
| pting | input-lanjian | 13.9 ± 0.4 | 12.9 | 16.8 | 20.24 ± 5.83 |
| pting | input-kcen | 13.9 ± 0.5 | 13.2 | 17.5 | 20.28 ± 5.86 |
| mattcl-py | input-lanjian | 13.9 ± 0.5 | 13.0 | 17.4 | 20.28 ± 5.85 |
| pting | input-pting | 13.9 ± 0.5 | 12.9 | 16.6 | 20.29 ± 5.86 |
| kcen | input-pting | 13.9 ± 0.5 | 13.3 | 17.3 | 20.30 ± 5.87 |
| kcen | input-kcen | 14.0 ± 0.6 | 13.0 | 17.0 | 20.33 ± 5.90 |
| kcen | input-lanjian | 14.0 ± 0.6 | 13.0 | 17.0 | 20.34 ± 5.89 |
| mattcl-py | input-kcen | 14.0 ± 0.6 | 13.1 | 17.7 | 20.35 ± 5.89 |
| kcen | input-mattcl | 14.0 ± 0.7 | 13.0 | 17.4 | 20.38 ± 5.92 |
| mattcl-py | input-mattcl | 14.0 ± 0.7 | 13.1 | 17.1 | 20.40 ± 5.92 |
| mattcl-py | input-pting | 14.0 ± 0.7 | 13.0 | 17.7 | 20.40 ± 5.94 |
| pting | input-mattcl | 15.1 ± 7.8 | 13.1 | 75.4 | 22.04 ± 12.93 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|