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
| lanjian | input-lanjian | 0.7 ± 0.2 | 0.0 | 1.3 | 1.03 ± 0.45 |
| lanjian | input-pting | 0.7 ± 0.2 | 0.1 | 0.9 | 1.04 ± 0.42 |
| mattcl | input-kcen | 0.7 ± 0.2 | 0.0 | 1.0 | 1.04 ± 0.46 |
| lanjian | input-kcen | 0.7 ± 0.1 | 0.0 | 1.0 | 1.07 ± 0.41 |
| mattcl | input-lanjian | 0.7 ± 0.2 | 0.1 | 0.9 | 1.08 ± 0.44 |
| mattcl | input-mattcl | 0.7 ± 0.1 | 0.1 | 0.9 | 1.09 ± 0.42 |
| mattcl | input-pting | 0.7 ± 0.1 | 0.1 | 0.9 | 1.12 ± 0.42 |
| mattcl-ts | input-mattcl | 9.0 ± 0.3 | 8.0 | 9.9 | 13.63 ± 4.47 |
| mattcl-ts | input-lanjian | 9.0 ± 0.3 | 8.2 | 9.7 | 13.64 ± 4.46 |
| mattcl-ts | input-pting | 9.0 ± 0.3 | 8.2 | 9.7 | 13.67 ± 4.48 |
| mattcl-ts | input-kcen | 9.1 ± 0.3 | 8.1 | 9.8 | 13.76 ± 4.51 |
| mattcl-py | input-mattcl | 13.9 ± 0.5 | 12.9 | 17.4 | 21.02 ± 6.89 |
| kcen | input-mattcl | 13.9 ± 0.5 | 13.0 | 16.8 | 21.02 ± 6.89 |
| pting | input-mattcl | 13.9 ± 0.5 | 13.2 | 17.3 | 21.04 ± 6.89 |
| mattcl-py | input-lanjian | 13.9 ± 0.5 | 13.2 | 16.4 | 21.05 ± 6.89 |
| kcen | input-lanjian | 13.9 ± 0.5 | 12.9 | 17.0 | 21.06 ± 6.91 |
| kcen | input-kcen | 13.9 ± 0.5 | 12.8 | 16.9 | 21.07 ± 6.90 |
| mattcl-py | input-kcen | 13.9 ± 0.6 | 13.1 | 17.2 | 21.09 ± 6.92 |
| pting | input-lanjian | 13.9 ± 0.5 | 12.9 | 16.4 | 21.09 ± 6.92 |
| pting | input-pting | 14.0 ± 0.6 | 13.1 | 16.6 | 21.14 ± 6.94 |
| mattcl-py | input-pting | 14.0 ± 0.7 | 12.9 | 17.4 | 21.18 ± 6.98 |
| kcen | input-pting | 14.0 ± 0.7 | 12.9 | 17.0 | 21.19 ± 6.98 |
| pting | input-kcen | 14.0 ± 0.6 | 13.0 | 17.1 | 21.20 ± 6.97 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|