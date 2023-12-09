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
| lanjian | input-mattcl | 0.7 ± 0.2 | 0.1 | 1.0 | 1.00 |
| lanjian | input-lanjian | 0.7 ± 0.2 | 0.1 | 1.1 | 1.00 ± 0.35 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.1 | 1.2 | 1.04 ± 0.35 |
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.2 | 1.05 ± 0.33 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.0 | 1.06 ± 0.34 |
| mattcl | input-kcen | 0.8 ± 0.1 | 0.1 | 1.0 | 1.07 ± 0.32 |
| lanjian | input-kcen | 0.8 ± 0.1 | 0.2 | 1.0 | 1.07 ± 0.31 |
| lanjian | input-pting | 0.8 ± 0.1 | 0.2 | 1.1 | 1.08 ± 0.31 |
| mattcl-ts | input-mattcl | 9.4 ± 0.4 | 8.4 | 10.4 | 12.74 ± 3.04 |
| mattcl-ts | input-pting | 9.4 ± 0.3 | 8.6 | 10.2 | 12.81 ± 3.06 |
| mattcl-ts | input-lanjian | 9.4 ± 0.3 | 8.5 | 10.2 | 12.81 ± 3.05 |
| mattcl-ts | input-kcen | 9.5 ± 0.3 | 8.5 | 10.4 | 12.88 ± 3.08 |
| kcen | input-mattcl | 13.8 ± 0.3 | 12.9 | 15.5 | 18.81 ± 4.46 |
| mattcl-py | input-lanjian | 13.9 ± 0.5 | 13.2 | 17.3 | 18.93 ± 4.53 |
| pting | input-mattcl | 13.9 ± 0.5 | 13.0 | 16.8 | 18.93 ± 4.52 |
| pting | input-pting | 13.9 ± 0.6 | 13.0 | 17.4 | 18.93 ± 4.54 |
| kcen | input-kcen | 13.9 ± 0.6 | 12.8 | 17.2 | 18.96 ± 4.55 |
| pting | input-kcen | 14.0 ± 0.7 | 13.0 | 17.2 | 18.97 ± 4.57 |
| kcen | input-pting | 14.0 ± 0.7 | 12.9 | 17.3 | 19.01 ± 4.57 |
| mattcl-py | input-mattcl | 14.0 ± 0.6 | 12.8 | 17.2 | 19.03 ± 4.57 |
| mattcl-py | input-pting | 14.0 ± 0.7 | 13.1 | 17.0 | 19.08 ± 4.61 |
| kcen | input-lanjian | 14.0 ± 0.7 | 13.0 | 17.7 | 19.08 ± 4.62 |
| pting | input-lanjian | 14.0 ± 0.7 | 13.0 | 17.0 | 19.09 ± 4.61 |
| mattcl-py | input-kcen | 14.1 ± 0.7 | 12.8 | 17.4 | 19.12 ± 4.62 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|