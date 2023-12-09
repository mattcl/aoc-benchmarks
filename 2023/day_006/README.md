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
| mattcl | input-kcen | 0.7 ± 0.2 | 0.1 | 1.3 | 1.00 |
| lanjian | input-kcen | 0.7 ± 0.2 | 0.1 | 1.3 | 1.03 ± 0.41 |
| lanjian | input-lanjian | 0.7 ± 0.2 | 0.1 | 1.0 | 1.06 ± 0.43 |
| lanjian | input-mattcl | 0.7 ± 0.2 | 0.0 | 1.3 | 1.07 ± 0.41 |
| mattcl | input-mattcl | 0.7 ± 0.2 | 0.1 | 1.0 | 1.07 ± 0.44 |
| lanjian | input-pting | 0.7 ± 0.1 | 0.1 | 0.9 | 1.10 ± 0.41 |
| mattcl | input-lanjian | 0.7 ± 0.2 | 0.1 | 0.9 | 1.10 ± 0.43 |
| mattcl | input-pting | 0.8 ± 0.1 | 0.1 | 0.9 | 1.11 ± 0.42 |
| mattcl-ts | input-lanjian | 9.4 ± 0.3 | 8.4 | 10.5 | 13.87 ± 4.49 |
| mattcl-ts | input-pting | 9.4 ± 0.4 | 8.6 | 10.7 | 13.91 ± 4.51 |
| mattcl-ts | input-mattcl | 9.4 ± 0.4 | 8.5 | 10.3 | 13.94 ± 4.51 |
| mattcl-ts | input-kcen | 9.4 ± 0.3 | 8.5 | 10.3 | 13.96 ± 4.52 |
| mattcl-py | input-pting | 13.9 ± 0.5 | 12.9 | 17.1 | 20.56 ± 6.66 |
| kcen | input-mattcl | 13.9 ± 0.4 | 13.0 | 16.5 | 20.59 ± 6.65 |
| pting | input-lanjian | 13.9 ± 0.4 | 13.1 | 17.0 | 20.61 ± 6.66 |
| pting | input-mattcl | 13.9 ± 0.5 | 13.0 | 17.0 | 20.62 ± 6.67 |
| kcen | input-pting | 13.9 ± 0.6 | 13.0 | 16.9 | 20.64 ± 6.69 |
| mattcl-py | input-lanjian | 13.9 ± 0.6 | 13.0 | 16.8 | 20.65 ± 6.70 |
| mattcl-py | input-kcen | 14.0 ± 0.5 | 13.1 | 17.2 | 20.66 ± 6.69 |
| pting | input-pting | 14.0 ± 0.6 | 12.9 | 17.3 | 20.67 ± 6.70 |
| kcen | input-kcen | 14.0 ± 0.6 | 13.1 | 17.3 | 20.68 ± 6.71 |
| pting | input-kcen | 14.0 ± 0.7 | 13.0 | 17.4 | 20.69 ± 6.72 |
| mattcl-py | input-mattcl | 14.0 ± 0.7 | 13.0 | 17.6 | 20.74 ± 6.75 |
| kcen | input-lanjian | 14.1 ± 2.6 | 13.0 | 50.0 | 20.94 ± 7.77 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|