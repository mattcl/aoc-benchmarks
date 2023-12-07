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
| lanjian | input-kcen | 0.7 ± 0.2 | 0.1 | 1.0 | 1.00 |
| lanjian | input-mattcl | 0.7 ± 0.2 | 0.1 | 1.0 | 1.02 ± 0.39 |
| lanjian | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.0 | 1.06 ± 0.43 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.0 | 1.07 ± 0.41 |
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.2 | 1.0 | 1.08 ± 0.41 |
| lanjian | input-pting | 0.8 ± 0.2 | 0.1 | 1.0 | 1.08 ± 0.42 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.2 | 1.0 | 1.10 ± 0.41 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.1 | 1.0 | 1.11 ± 0.42 |
| mattcl-ts | input-kcen | 9.1 ± 0.3 | 8.4 | 10.0 | 12.68 ± 3.94 |
| mattcl-ts | input-lanjian | 9.1 ± 0.3 | 8.1 | 10.2 | 12.75 ± 3.97 |
| mattcl-ts | input-pting | 9.2 ± 0.3 | 8.3 | 10.3 | 12.77 ± 3.98 |
| mattcl-ts | input-mattcl | 10.4 ± 6.4 | 8.1 | 52.5 | 14.49 ± 9.97 |
| kcen | input-mattcl | 14.4 ± 0.6 | 13.5 | 16.8 | 20.13 ± 6.27 |
| mattcl-py | input-mattcl | 14.4 ± 0.6 | 13.3 | 17.5 | 20.13 ± 6.28 |
| mattcl-py | input-kcen | 14.5 ± 0.5 | 13.4 | 17.1 | 20.18 ± 6.28 |
| pting | input-kcen | 14.5 ± 0.5 | 13.4 | 17.2 | 20.21 ± 6.29 |
| mattcl-py | input-lanjian | 14.5 ± 0.6 | 13.4 | 17.5 | 20.26 ± 6.31 |
| kcen | input-pting | 14.6 ± 0.5 | 13.5 | 17.2 | 20.30 ± 6.31 |
| pting | input-pting | 14.6 ± 0.6 | 13.6 | 17.2 | 20.39 ± 6.36 |
| pting | input-mattcl | 14.7 ± 0.6 | 13.6 | 17.0 | 20.43 ± 6.36 |
| pting | input-lanjian | 15.0 ± 1.9 | 13.4 | 21.9 | 20.93 ± 7.00 |
| mattcl-py | input-pting | 15.1 ± 2.0 | 13.4 | 24.0 | 21.02 ± 7.06 |
| kcen | input-kcen | 15.1 ± 2.0 | 13.5 | 23.8 | 21.11 ± 7.09 |
| kcen | input-lanjian | 15.4 ± 2.3 | 13.5 | 28.5 | 21.41 ± 7.37 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|