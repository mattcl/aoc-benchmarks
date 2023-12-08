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
| lanjian | input-mattcl | 0.7 ± 0.2 | 0.1 | 0.9 | 1.00 |
| lanjian | input-pting | 0.7 ± 0.2 | 0.1 | 0.9 | 1.05 ± 0.38 |
| lanjian | input-lanjian | 0.7 ± 0.2 | 0.1 | 0.9 | 1.05 ± 0.36 |
| mattcl | input-lanjian | 0.7 ± 0.2 | 0.1 | 0.9 | 1.08 ± 0.39 |
| mattcl | input-kcen | 0.7 ± 0.2 | 0.0 | 0.9 | 1.09 ± 0.37 |
| lanjian | input-kcen | 0.7 ± 0.1 | 0.3 | 1.0 | 1.09 ± 0.35 |
| mattcl | input-pting | 0.8 ± 0.1 | 0.3 | 1.3 | 1.11 ± 0.36 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.3 | 1.12 ± 0.39 |
| mattcl-ts | input-pting | 9.4 ± 0.4 | 8.3 | 10.8 | 13.68 ± 3.74 |
| mattcl-ts | input-lanjian | 9.4 ± 0.4 | 8.1 | 10.7 | 13.70 ± 3.74 |
| mattcl-ts | input-kcen | 9.4 ± 0.3 | 8.2 | 10.3 | 13.70 ± 3.74 |
| mattcl-ts | input-mattcl | 9.4 ± 0.4 | 8.3 | 10.4 | 13.74 ± 3.76 |
| kcen | input-mattcl | 14.0 ± 0.6 | 12.9 | 17.5 | 20.48 ± 5.60 |
| kcen | input-lanjian | 14.1 ± 0.5 | 13.1 | 17.2 | 20.51 ± 5.61 |
| mattcl-py | input-pting | 14.1 ± 0.6 | 13.3 | 17.1 | 20.51 ± 5.62 |
| kcen | input-pting | 14.1 ± 0.6 | 12.7 | 17.0 | 20.52 ± 5.62 |
| pting | input-kcen | 14.1 ± 0.6 | 13.1 | 17.5 | 20.55 ± 5.62 |
| mattcl-py | input-kcen | 14.1 ± 0.7 | 13.1 | 19.0 | 20.57 ± 5.67 |
| mattcl-py | input-mattcl | 14.1 ± 0.6 | 13.0 | 17.2 | 20.59 ± 5.65 |
| mattcl-py | input-lanjian | 14.1 ± 0.6 | 13.4 | 17.6 | 20.61 ± 5.65 |
| pting | input-lanjian | 14.2 ± 0.6 | 13.1 | 17.5 | 20.63 ± 5.66 |
| kcen | input-kcen | 14.2 ± 0.8 | 13.2 | 17.4 | 20.68 ± 5.71 |
| pting | input-pting | 14.2 ± 1.8 | 13.3 | 38.5 | 20.77 ± 6.20 |
| pting | input-mattcl | 14.3 ± 2.5 | 12.7 | 48.4 | 20.78 ± 6.72 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|