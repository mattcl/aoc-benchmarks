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
| lanjian | input-kcen | 0.7 ± 0.2 | 0.1 | 0.9 | 1.00 |
| lanjian | input-mattcl | 0.7 ± 0.2 | 0.0 | 0.9 | 1.02 ± 0.38 |
| lanjian | input-pting | 0.7 ± 0.2 | 0.0 | 1.1 | 1.04 ± 0.38 |
| mattcl | input-mattcl | 0.7 ± 0.2 | 0.1 | 1.1 | 1.04 ± 0.37 |
| mattcl | input-kcen | 0.7 ± 0.2 | 0.1 | 1.0 | 1.05 ± 0.39 |
| mattcl | input-lanjian | 0.7 ± 0.2 | 0.1 | 0.9 | 1.08 ± 0.39 |
| lanjian | input-lanjian | 0.7 ± 0.1 | 0.1 | 1.2 | 1.08 ± 0.36 |
| mattcl | input-pting | 0.8 ± 0.1 | 0.1 | 1.2 | 1.14 ± 0.37 |
| mattcl-ts | input-pting | 9.3 ± 0.3 | 8.4 | 10.1 | 13.57 ± 3.74 |
| mattcl-ts | input-mattcl | 9.4 ± 0.3 | 8.5 | 10.2 | 13.59 ± 3.74 |
| mattcl-ts | input-lanjian | 9.4 ± 0.3 | 8.1 | 10.4 | 13.62 ± 3.75 |
| mattcl-ts | input-kcen | 9.4 ± 0.4 | 8.1 | 10.6 | 13.63 ± 3.76 |
| kcen | input-lanjian | 13.9 ± 0.4 | 12.9 | 16.0 | 20.18 ± 5.54 |
| mattcl-py | input-lanjian | 13.9 ± 0.5 | 12.9 | 17.2 | 20.25 ± 5.58 |
| mattcl-py | input-kcen | 13.9 ± 0.5 | 13.0 | 17.2 | 20.26 ± 5.58 |
| kcen | input-kcen | 14.0 ± 0.6 | 13.2 | 16.9 | 20.31 ± 5.60 |
| kcen | input-pting | 14.0 ± 0.6 | 13.1 | 17.5 | 20.32 ± 5.62 |
| mattcl-py | input-mattcl | 14.0 ± 0.6 | 13.1 | 17.4 | 20.33 ± 5.61 |
| pting | input-pting | 14.0 ± 0.6 | 12.9 | 17.6 | 20.35 ± 5.62 |
| pting | input-kcen | 14.0 ± 0.7 | 13.1 | 17.8 | 20.36 ± 5.64 |
| mattcl-py | input-pting | 14.0 ± 0.6 | 12.9 | 17.2 | 20.39 ± 5.63 |
| pting | input-mattcl | 14.0 ± 0.7 | 13.0 | 17.2 | 20.40 ± 5.65 |
| kcen | input-mattcl | 14.2 ± 4.1 | 12.9 | 71.8 | 20.62 ± 8.22 |
| pting | input-lanjian | 14.6 ± 4.8 | 12.9 | 56.9 | 21.22 ± 9.09 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|