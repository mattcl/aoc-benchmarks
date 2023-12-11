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
| lanjian | input-pting | 0.7 ± 0.2 | 0.1 | 1.2 | 1.00 |
| lanjian | input-mattcl | 0.7 ± 0.2 | 0.1 | 1.3 | 1.03 ± 0.39 |
| mattcl | input-lanjian | 0.7 ± 0.2 | 0.0 | 1.0 | 1.05 ± 0.44 |
| lanjian | input-lanjian | 0.7 ± 0.2 | 0.1 | 1.0 | 1.05 ± 0.39 |
| mattcl | input-pting | 0.7 ± 0.2 | 0.0 | 0.9 | 1.06 ± 0.41 |
| mattcl | input-kcen | 0.7 ± 0.2 | 0.0 | 1.1 | 1.07 ± 0.42 |
| mattcl | input-mattcl | 0.7 ± 0.2 | 0.1 | 1.3 | 1.07 ± 0.41 |
| lanjian | input-kcen | 0.7 ± 0.2 | 0.1 | 1.0 | 1.07 ± 0.38 |
| mattcl-ts | input-lanjian | 9.7 ± 0.4 | 8.9 | 10.4 | 14.32 ± 4.21 |
| mattcl-ts | input-mattcl | 9.7 ± 0.4 | 9.0 | 10.8 | 14.39 ± 4.24 |
| mattcl-ts | input-kcen | 9.8 ± 0.4 | 8.8 | 10.7 | 14.45 ± 4.25 |
| mattcl-ts | input-pting | 9.8 ± 0.4 | 8.5 | 10.7 | 14.49 ± 4.26 |
| pting | input-lanjian | 13.9 ± 0.5 | 13.0 | 16.8 | 20.52 ± 6.03 |
| pting | input-mattcl | 13.9 ± 0.5 | 13.0 | 17.1 | 20.55 ± 6.04 |
| mattcl-py | input-pting | 13.9 ± 0.6 | 13.0 | 17.7 | 20.55 ± 6.05 |
| mattcl-py | input-mattcl | 13.9 ± 0.5 | 12.8 | 16.8 | 20.57 ± 6.05 |
| pting | input-kcen | 13.9 ± 0.5 | 12.9 | 17.4 | 20.58 ± 6.06 |
| pting | input-pting | 13.9 ± 0.4 | 13.1 | 16.3 | 20.59 ± 6.04 |
| kcen | input-pting | 13.9 ± 0.5 | 12.9 | 16.8 | 20.60 ± 6.05 |
| kcen | input-mattcl | 13.9 ± 0.5 | 12.8 | 16.8 | 20.60 ± 6.06 |
| kcen | input-lanjian | 13.9 ± 0.6 | 12.8 | 17.3 | 20.60 ± 6.08 |
| mattcl-py | input-kcen | 13.9 ± 0.6 | 13.1 | 17.7 | 20.62 ± 6.08 |
| mattcl-py | input-lanjian | 14.0 ± 0.5 | 13.1 | 17.3 | 20.63 ± 6.07 |
| kcen | input-kcen | 14.2 ± 3.8 | 13.0 | 66.5 | 20.96 ± 8.26 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|