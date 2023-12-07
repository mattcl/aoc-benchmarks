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
| lanjian | input-pting | 0.7 ± 0.2 | 0.1 | 1.0 | 1.00 |
| mattcl | input-lanjian | 0.7 ± 0.2 | 0.0 | 1.1 | 1.00 ± 0.32 |
| lanjian | input-lanjian | 0.7 ± 0.2 | 0.1 | 1.5 | 1.00 ± 0.32 |
| lanjian | input-kcen | 0.8 ± 0.2 | 0.1 | 1.0 | 1.01 ± 0.31 |
| lanjian | input-mattcl | 0.8 ± 0.1 | 0.1 | 0.9 | 1.01 ± 0.29 |
| mattcl | input-pting | 0.8 ± 0.1 | 0.1 | 0.9 | 1.02 ± 0.28 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.3 | 1.03 ± 0.31 |
| mattcl | input-kcen | 0.8 ± 0.1 | 0.2 | 0.9 | 1.05 ± 0.28 |
| mattcl-ts | input-lanjian | 9.2 ± 0.3 | 8.2 | 10.1 | 12.34 ± 2.66 |
| mattcl-ts | input-mattcl | 9.2 ± 0.4 | 8.1 | 10.1 | 12.39 ± 2.68 |
| mattcl-ts | input-pting | 9.3 ± 0.3 | 8.2 | 10.3 | 12.42 ± 2.67 |
| mattcl-ts | input-kcen | 9.3 ± 0.3 | 8.2 | 10.3 | 12.45 ± 2.68 |
| pting | input-kcen | 13.9 ± 0.4 | 13.0 | 16.9 | 18.66 ± 4.01 |
| kcen | input-pting | 14.0 ± 0.4 | 13.1 | 16.4 | 18.73 ± 4.02 |
| pting | input-lanjian | 14.0 ± 0.5 | 13.1 | 16.5 | 18.74 ± 4.03 |
| kcen | input-mattcl | 14.0 ± 0.5 | 13.4 | 17.1 | 18.77 ± 4.05 |
| mattcl-py | input-pting | 14.0 ± 0.5 | 12.8 | 16.5 | 18.78 ± 4.06 |
| mattcl-py | input-mattcl | 14.0 ± 0.5 | 13.2 | 17.5 | 18.78 ± 4.06 |
| kcen | input-lanjian | 14.0 ± 0.6 | 13.0 | 16.8 | 18.78 ± 4.06 |
| mattcl-py | input-kcen | 14.0 ± 0.7 | 12.9 | 18.3 | 18.84 ± 4.12 |
| mattcl-py | input-lanjian | 14.1 ± 0.7 | 13.0 | 17.4 | 18.87 ± 4.11 |
| kcen | input-kcen | 14.1 ± 0.5 | 13.1 | 17.2 | 18.88 ± 4.08 |
| pting | input-mattcl | 14.1 ± 0.7 | 13.1 | 17.6 | 18.90 ± 4.13 |
| pting | input-pting | 14.9 ± 6.1 | 13.1 | 57.4 | 19.99 ± 9.23 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|