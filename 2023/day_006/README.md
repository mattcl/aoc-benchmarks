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
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.0 | 1.00 |
| lanjian | input-pting | 0.8 ± 0.2 | 0.1 | 1.1 | 1.01 ± 0.39 |
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.2 | 1.03 ± 0.43 |
| lanjian | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.0 | 1.04 ± 0.42 |
| lanjian | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.0 | 1.04 ± 0.39 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.2 | 1.5 | 1.06 ± 0.40 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.2 | 1.0 | 1.07 ± 0.39 |
| lanjian | input-kcen | 0.8 ± 0.2 | 0.2 | 1.4 | 1.08 ± 0.40 |
| mattcl-ts | input-lanjian | 9.2 ± 0.4 | 8.0 | 10.1 | 11.91 ± 3.77 |
| mattcl-ts | input-mattcl | 9.2 ± 0.4 | 8.3 | 10.1 | 11.94 ± 3.78 |
| mattcl-ts | input-pting | 9.3 ± 0.4 | 8.3 | 12.3 | 11.99 ± 3.81 |
| mattcl-ts | input-kcen | 9.4 ± 2.7 | 8.2 | 46.4 | 12.17 ± 5.14 |
| kcen | input-kcen | 14.1 ± 0.6 | 13.1 | 17.4 | 18.29 ± 5.80 |
| mattcl-py | input-kcen | 14.2 ± 0.5 | 12.9 | 16.9 | 18.31 ± 5.79 |
| mattcl-py | input-pting | 14.2 ± 0.5 | 13.2 | 17.2 | 18.31 ± 5.80 |
| kcen | input-pting | 14.2 ± 0.5 | 13.0 | 16.7 | 18.31 ± 5.79 |
| mattcl-py | input-mattcl | 14.2 ± 0.5 | 13.0 | 17.5 | 18.35 ± 5.81 |
| mattcl-py | input-lanjian | 14.2 ± 0.6 | 13.3 | 17.5 | 18.35 ± 5.81 |
| kcen | input-mattcl | 14.2 ± 0.7 | 13.2 | 17.4 | 18.37 ± 5.84 |
| pting | input-pting | 14.2 ± 0.6 | 13.3 | 17.2 | 18.37 ± 5.82 |
| pting | input-mattcl | 14.3 ± 0.7 | 13.3 | 17.8 | 18.43 ± 5.86 |
| kcen | input-lanjian | 14.3 ± 0.8 | 13.1 | 17.4 | 18.51 ± 5.90 |
| pting | input-lanjian | 14.3 ± 0.7 | 13.2 | 17.7 | 18.54 ± 5.91 |
| pting | input-kcen | 14.4 ± 2.5 | 13.1 | 48.8 | 18.60 ± 6.70 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|