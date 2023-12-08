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
| lanjian | input-lanjian | 0.7 ± 0.2 | 0.0 | 1.0 | 1.00 |
| lanjian | input-pting | 0.7 ± 0.2 | 0.0 | 0.9 | 1.04 ± 0.41 |
| lanjian | input-kcen | 0.7 ± 0.2 | 0.1 | 1.0 | 1.05 ± 0.40 |
| mattcl | input-mattcl | 0.7 ± 0.2 | 0.0 | 0.9 | 1.05 ± 0.42 |
| lanjian | input-mattcl | 0.7 ± 0.2 | 0.1 | 1.4 | 1.07 ± 0.39 |
| mattcl | input-kcen | 0.7 ± 0.2 | 0.1 | 1.3 | 1.10 ± 0.41 |
| mattcl | input-lanjian | 0.8 ± 0.1 | 0.3 | 1.0 | 1.13 ± 0.39 |
| mattcl | input-pting | 0.8 ± 0.1 | 0.0 | 1.0 | 1.15 ± 0.40 |
| mattcl-ts | input-kcen | 9.3 ± 0.3 | 8.4 | 10.1 | 13.82 ± 4.10 |
| mattcl-ts | input-mattcl | 9.3 ± 0.3 | 8.4 | 10.3 | 13.87 ± 4.12 |
| mattcl-ts | input-pting | 9.3 ± 0.4 | 8.3 | 10.3 | 13.89 ± 4.12 |
| mattcl-ts | input-lanjian | 9.4 ± 0.3 | 8.3 | 10.1 | 13.99 ± 4.15 |
| kcen | input-pting | 13.9 ± 0.5 | 12.9 | 17.2 | 20.67 ± 6.13 |
| pting | input-lanjian | 13.9 ± 0.5 | 13.3 | 17.1 | 20.69 ± 6.13 |
| mattcl-py | input-mattcl | 13.9 ± 0.5 | 13.2 | 17.5 | 20.70 ± 6.15 |
| pting | input-pting | 13.9 ± 0.5 | 12.9 | 16.7 | 20.72 ± 6.16 |
| mattcl-py | input-pting | 14.0 ± 0.6 | 13.1 | 17.5 | 20.76 ± 6.18 |
| pting | input-mattcl | 14.0 ± 0.6 | 13.3 | 17.2 | 20.77 ± 6.18 |
| mattcl-py | input-lanjian | 14.0 ± 0.7 | 12.8 | 17.8 | 20.79 ± 6.20 |
| kcen | input-mattcl | 14.0 ± 0.6 | 12.9 | 17.7 | 20.79 ± 6.19 |
| pting | input-kcen | 14.0 ± 0.6 | 13.3 | 17.2 | 20.85 ± 6.22 |
| kcen | input-lanjian | 14.0 ± 0.7 | 12.8 | 17.2 | 20.86 ± 6.23 |
| kcen | input-kcen | 14.0 ± 0.7 | 13.1 | 17.1 | 20.87 ± 6.24 |
| mattcl-py | input-kcen | 14.2 ± 3.1 | 13.1 | 56.5 | 21.21 ± 7.76 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|