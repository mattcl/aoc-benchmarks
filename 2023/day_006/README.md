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
| lanjian | input-mattcl | 0.7 ± 0.2 | 0.0 | 0.9 | 1.00 |
| mattcl | input-lanjian | 0.7 ± 0.2 | 0.0 | 1.0 | 1.02 ± 0.42 |
| mattcl | input-pting | 0.7 ± 0.2 | 0.1 | 0.9 | 1.03 ± 0.42 |
| lanjian | input-kcen | 0.7 ± 0.2 | 0.0 | 1.2 | 1.03 ± 0.42 |
| lanjian | input-lanjian | 0.7 ± 0.2 | 0.1 | 1.0 | 1.03 ± 0.42 |
| mattcl | input-kcen | 0.7 ± 0.2 | 0.0 | 1.3 | 1.04 ± 0.44 |
| mattcl | input-mattcl | 0.7 ± 0.1 | 0.1 | 0.9 | 1.08 ± 0.41 |
| lanjian | input-pting | 0.7 ± 0.1 | 0.4 | 1.1 | 1.12 ± 0.39 |
| mattcl-ts | input-pting | 9.1 ± 0.3 | 8.2 | 10.4 | 14.02 ± 4.45 |
| mattcl-ts | input-mattcl | 9.1 ± 0.3 | 8.3 | 10.4 | 14.04 ± 4.46 |
| mattcl-ts | input-lanjian | 9.2 ± 0.4 | 8.3 | 12.5 | 14.17 ± 4.50 |
| mattcl-ts | input-kcen | 9.2 ± 0.4 | 8.2 | 10.6 | 14.17 ± 4.50 |
| mattcl-py | input-lanjian | 13.9 ± 0.5 | 12.9 | 17.5 | 21.28 ± 6.75 |
| mattcl-py | input-mattcl | 13.9 ± 0.4 | 12.8 | 17.0 | 21.30 ± 6.74 |
| pting | input-mattcl | 13.9 ± 0.5 | 12.9 | 17.0 | 21.35 ± 6.78 |
| kcen | input-pting | 13.9 ± 0.6 | 13.3 | 17.0 | 21.36 ± 6.79 |
| mattcl-py | input-kcen | 13.9 ± 0.5 | 12.9 | 17.4 | 21.36 ± 6.79 |
| pting | input-kcen | 13.9 ± 0.6 | 12.9 | 17.2 | 21.36 ± 6.79 |
| kcen | input-mattcl | 13.9 ± 0.6 | 12.9 | 17.1 | 21.40 ± 6.81 |
| pting | input-lanjian | 14.0 ± 0.7 | 13.0 | 17.1 | 21.42 ± 6.84 |
| kcen | input-lanjian | 14.0 ± 0.6 | 13.0 | 17.4 | 21.42 ± 6.81 |
| pting | input-pting | 14.0 ± 0.5 | 13.1 | 17.1 | 21.45 ± 6.81 |
| kcen | input-kcen | 14.0 ± 0.6 | 12.9 | 17.2 | 21.45 ± 6.83 |
| mattcl-py | input-pting | 14.0 ± 0.7 | 13.1 | 17.6 | 21.52 ± 6.87 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|