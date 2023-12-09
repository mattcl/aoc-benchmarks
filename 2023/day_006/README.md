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
| mattcl | input-pting | 0.8 ± 0.2 | 0.1 | 1.0 | 1.00 |
| lanjian | input-kcen | 0.8 ± 0.2 | 0.2 | 1.0 | 1.02 ± 0.32 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.2 | 1.03 ± 0.32 |
| lanjian | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.3 | 1.04 ± 0.31 |
| lanjian | input-pting | 0.9 ± 0.1 | 0.4 | 1.0 | 1.04 ± 0.30 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.1 | 1.05 ± 0.32 |
| lanjian | input-mattcl | 0.9 ± 0.1 | 0.4 | 1.4 | 1.07 ± 0.29 |
| mattcl | input-mattcl | 0.9 ± 0.1 | 0.5 | 1.2 | 1.09 ± 0.30 |
| mattcl-ts | input-kcen | 9.6 ± 0.4 | 8.4 | 10.7 | 11.57 ± 2.71 |
| mattcl-ts | input-pting | 9.6 ± 0.4 | 8.3 | 10.5 | 11.59 ± 2.72 |
| mattcl-ts | input-lanjian | 9.6 ± 0.4 | 8.5 | 10.9 | 11.65 ± 2.73 |
| mattcl-ts | input-mattcl | 10.1 ± 5.6 | 8.5 | 73.3 | 12.26 ± 7.39 |
| pting | input-lanjian | 14.1 ± 0.5 | 13.3 | 17.5 | 17.06 ± 4.00 |
| pting | input-pting | 14.1 ± 0.4 | 13.2 | 16.9 | 17.09 ± 3.98 |
| kcen | input-pting | 14.1 ± 0.6 | 13.2 | 17.7 | 17.11 ± 4.02 |
| kcen | input-mattcl | 14.2 ± 0.6 | 13.1 | 17.4 | 17.13 ± 4.03 |
| mattcl-py | input-lanjian | 14.2 ± 0.6 | 13.4 | 17.3 | 17.14 ± 4.03 |
| pting | input-kcen | 14.2 ± 0.5 | 13.2 | 17.3 | 17.14 ± 4.01 |
| mattcl-py | input-kcen | 14.2 ± 0.7 | 13.2 | 17.3 | 17.19 ± 4.06 |
| pting | input-mattcl | 14.2 ± 0.7 | 13.2 | 17.8 | 17.19 ± 4.06 |
| kcen | input-kcen | 14.2 ± 0.6 | 13.2 | 17.2 | 17.21 ± 4.04 |
| mattcl-py | input-pting | 14.3 ± 0.7 | 13.2 | 17.7 | 17.26 ± 4.07 |
| mattcl-py | input-mattcl | 14.5 ± 3.8 | 13.2 | 66.4 | 17.51 ± 6.08 |
| kcen | input-lanjian | 14.5 ± 2.8 | 13.3 | 52.4 | 17.57 ± 5.27 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|