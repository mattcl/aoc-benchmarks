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
| lanjian | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.1 | 1.00 |
| lanjian | input-pting | 0.8 ± 0.2 | 0.1 | 1.1 | 1.02 ± 0.34 |
| lanjian | input-kcen | 0.8 ± 0.2 | 0.1 | 1.0 | 1.02 ± 0.33 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.2 | 1.3 | 1.06 ± 0.34 |
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.2 | 1.2 | 1.06 ± 0.34 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.1 | 1.5 | 1.07 ± 0.34 |
| lanjian | input-lanjian | 0.8 ± 0.1 | 0.4 | 1.0 | 1.10 ± 0.31 |
| mattcl | input-pting | 1.0 ± 3.0 | 0.1 | 43.7 | 1.29 ± 4.04 |
| mattcl-ts | input-kcen | 9.5 ± 0.4 | 8.6 | 10.4 | 12.57 ± 3.22 |
| mattcl-ts | input-pting | 9.6 ± 0.4 | 8.6 | 10.8 | 12.67 ± 3.25 |
| mattcl-ts | input-lanjian | 9.6 ± 0.3 | 8.5 | 10.5 | 12.68 ± 3.24 |
| mattcl-ts | input-mattcl | 9.6 ± 0.3 | 8.8 | 10.4 | 12.74 ± 3.26 |
| mattcl-py | input-pting | 14.1 ± 0.5 | 13.1 | 17.3 | 18.61 ± 4.76 |
| mattcl-py | input-mattcl | 14.1 ± 0.5 | 12.9 | 16.6 | 18.62 ± 4.76 |
| mattcl-py | input-kcen | 14.1 ± 0.6 | 12.9 | 17.4 | 18.66 ± 4.79 |
| mattcl-py | input-lanjian | 14.1 ± 0.5 | 13.0 | 16.8 | 18.67 ± 4.78 |
| kcen | input-kcen | 14.1 ± 0.5 | 13.1 | 17.2 | 18.71 ± 4.79 |
| pting | input-mattcl | 14.1 ± 0.6 | 13.2 | 17.0 | 18.73 ± 4.80 |
| pting | input-kcen | 14.2 ± 0.7 | 13.0 | 17.7 | 18.77 ± 4.84 |
| pting | input-pting | 14.2 ± 0.7 | 13.0 | 17.4 | 18.77 ± 4.84 |
| kcen | input-lanjian | 14.2 ± 0.7 | 13.2 | 17.9 | 18.81 ± 4.85 |
| kcen | input-pting | 14.2 ± 0.6 | 13.1 | 17.9 | 18.81 ± 4.84 |
| pting | input-lanjian | 14.3 ± 0.9 | 13.3 | 17.9 | 18.98 ± 4.94 |
| kcen | input-mattcl | 14.5 ± 3.7 | 13.0 | 66.1 | 19.15 ± 6.93 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|