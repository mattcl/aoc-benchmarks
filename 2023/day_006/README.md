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
| lanjian | input-mattcl | 0.7 ± 0.2 | 0.1 | 1.0 | 1.03 ± 0.41 |
| mattcl | input-mattcl | 0.7 ± 0.2 | 0.1 | 1.3 | 1.04 ± 0.44 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.1 | 1.1 | 1.07 ± 0.41 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.1 | 1.3 | 1.07 ± 0.41 |
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.1 | 1.10 ± 0.40 |
| lanjian | input-lanjian | 0.8 ± 0.1 | 0.1 | 1.0 | 1.11 ± 0.38 |
| lanjian | input-pting | 0.8 ± 0.1 | 0.2 | 1.1 | 1.12 ± 0.38 |
| mattcl-ts | input-lanjian | 9.9 ± 0.4 | 8.8 | 10.9 | 13.86 ± 4.03 |
| mattcl-ts | input-kcen | 9.9 ± 0.4 | 8.9 | 10.8 | 13.89 ± 4.04 |
| mattcl-ts | input-pting | 9.9 ± 0.4 | 8.8 | 10.9 | 13.93 ± 4.05 |
| mattcl-ts | input-mattcl | 9.9 ± 0.3 | 9.1 | 10.7 | 13.94 ± 4.05 |
| mattcl-py | input-pting | 13.9 ± 0.4 | 13.0 | 16.5 | 19.52 ± 5.66 |
| kcen | input-lanjian | 14.0 ± 0.5 | 13.2 | 16.8 | 19.59 ± 5.69 |
| mattcl-py | input-mattcl | 14.0 ± 0.6 | 12.8 | 17.1 | 19.60 ± 5.71 |
| mattcl-py | input-lanjian | 14.0 ± 0.6 | 12.8 | 17.2 | 19.60 ± 5.71 |
| kcen | input-kcen | 14.0 ± 0.6 | 12.9 | 16.9 | 19.65 ± 5.73 |
| kcen | input-mattcl | 14.0 ± 0.6 | 13.0 | 17.0 | 19.66 ± 5.74 |
| mattcl-py | input-kcen | 14.0 ± 0.6 | 12.9 | 16.8 | 19.66 ± 5.74 |
| pting | input-kcen | 14.0 ± 0.6 | 13.1 | 17.2 | 19.68 ± 5.74 |
| pting | input-pting | 14.0 ± 0.6 | 13.0 | 16.9 | 19.68 ± 5.73 |
| pting | input-lanjian | 14.0 ± 0.6 | 13.0 | 17.0 | 19.69 ± 5.75 |
| pting | input-mattcl | 14.1 ± 2.7 | 12.9 | 51.5 | 19.81 ± 6.85 |
| kcen | input-pting | 14.2 ± 3.0 | 13.0 | 55.7 | 20.00 ± 7.15 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|