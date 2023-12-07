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
| lanjian | input-kcen | 0.7 ± 0.2 | 0.2 | 1.2 | 1.00 |
| lanjian | input-lanjian | 0.8 ± 0.2 | 0.2 | 1.0 | 1.04 ± 0.40 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.1 | 1.0 | 1.07 ± 0.42 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.3 | 1.07 ± 0.41 |
| lanjian | input-mattcl | 0.8 ± 0.2 | 0.2 | 1.2 | 1.08 ± 0.39 |
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.2 | 1.0 | 1.09 ± 0.40 |
| lanjian | input-pting | 0.8 ± 0.2 | 0.1 | 2.5 | 1.10 ± 0.42 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.1 | 1.0 | 1.12 ± 0.39 |
| mattcl-ts | input-lanjian | 9.4 ± 0.4 | 8.2 | 10.2 | 12.93 ± 3.80 |
| mattcl-ts | input-kcen | 9.4 ± 0.4 | 8.5 | 10.8 | 12.96 ± 3.81 |
| mattcl-ts | input-pting | 9.4 ± 0.4 | 8.6 | 10.7 | 12.98 ± 3.81 |
| mattcl-ts | input-mattcl | 9.5 ± 0.3 | 8.4 | 10.5 | 13.04 ± 3.83 |
| mattcl-py | input-pting | 14.0 ± 0.5 | 13.0 | 17.7 | 19.26 ± 5.66 |
| pting | input-kcen | 14.0 ± 0.6 | 12.8 | 17.6 | 19.27 ± 5.68 |
| pting | input-lanjian | 14.0 ± 0.5 | 12.9 | 16.8 | 19.29 ± 5.67 |
| kcen | input-lanjian | 14.0 ± 0.6 | 12.8 | 17.0 | 19.29 ± 5.68 |
| kcen | input-kcen | 14.0 ± 0.5 | 13.1 | 16.9 | 19.29 ± 5.67 |
| kcen | input-mattcl | 14.0 ± 0.6 | 13.3 | 17.3 | 19.33 ± 5.68 |
| mattcl-py | input-lanjian | 14.0 ± 0.7 | 13.0 | 17.7 | 19.33 ± 5.70 |
| mattcl-py | input-mattcl | 14.0 ± 0.7 | 13.1 | 17.5 | 19.38 ± 5.73 |
| pting | input-mattcl | 14.1 ± 0.7 | 13.4 | 17.4 | 19.39 ± 5.72 |
| kcen | input-pting | 14.1 ± 0.6 | 12.9 | 17.3 | 19.40 ± 5.72 |
| mattcl-py | input-kcen | 14.1 ± 0.7 | 13.3 | 17.7 | 19.42 ± 5.75 |
| pting | input-pting | 14.3 ± 3.3 | 12.9 | 60.0 | 19.68 ± 7.33 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|