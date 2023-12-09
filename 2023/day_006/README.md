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
| lanjian | input-mattcl | 0.8 ± 0.2 | 0.2 | 1.2 | 1.00 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.1 | 1.3 | 1.01 ± 0.35 |
| lanjian | input-pting | 0.8 ± 0.2 | 0.4 | 1.1 | 1.02 ± 0.31 |
| lanjian | input-lanjian | 0.8 ± 0.2 | 0.2 | 1.5 | 1.02 ± 0.33 |
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.2 | 1.4 | 1.05 ± 0.33 |
| lanjian | input-kcen | 0.8 ± 0.2 | 0.2 | 1.4 | 1.05 ± 0.31 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.2 | 1.2 | 1.05 ± 0.31 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.3 | 1.4 | 1.06 ± 0.32 |
| mattcl-ts | input-kcen | 9.5 ± 0.3 | 8.8 | 10.4 | 11.79 ± 2.79 |
| mattcl-ts | input-mattcl | 9.6 ± 0.4 | 8.6 | 10.8 | 11.91 ± 2.83 |
| mattcl-ts | input-lanjian | 9.7 ± 0.3 | 8.7 | 10.6 | 11.96 ± 2.82 |
| mattcl-ts | input-pting | 9.8 ± 2.1 | 8.5 | 39.0 | 12.07 ± 3.84 |
| mattcl-py | input-mattcl | 14.1 ± 0.5 | 12.9 | 17.0 | 17.37 ± 4.11 |
| kcen | input-kcen | 14.1 ± 0.7 | 13.3 | 17.4 | 17.47 ± 4.17 |
| pting | input-lanjian | 14.1 ± 0.6 | 13.0 | 17.9 | 17.47 ± 4.15 |
| mattcl-py | input-lanjian | 14.1 ± 0.6 | 13.1 | 16.7 | 17.48 ± 4.14 |
| kcen | input-mattcl | 14.1 ± 0.6 | 13.1 | 17.5 | 17.49 ± 4.15 |
| mattcl-py | input-kcen | 14.2 ± 0.6 | 13.1 | 17.6 | 17.52 ± 4.15 |
| mattcl-py | input-pting | 14.2 ± 0.7 | 13.3 | 17.3 | 17.52 ± 4.17 |
| kcen | input-lanjian | 14.2 ± 0.7 | 13.3 | 18.3 | 17.55 ± 4.19 |
| pting | input-mattcl | 14.2 ± 0.7 | 13.1 | 18.3 | 17.55 ± 4.20 |
| kcen | input-pting | 14.2 ± 0.7 | 13.0 | 17.7 | 17.58 ± 4.19 |
| pting | input-pting | 14.2 ± 0.7 | 13.4 | 17.4 | 17.60 ± 4.19 |
| pting | input-kcen | 14.3 ± 0.8 | 13.4 | 17.6 | 17.67 ± 4.23 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|