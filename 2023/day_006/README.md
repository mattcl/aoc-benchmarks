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
| lanjian | input-pting | 0.8 ± 0.2 | 0.2 | 1.2 | 1.00 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.5 | 1.05 ± 0.33 |
| lanjian | input-mattcl | 0.9 ± 0.1 | 0.3 | 1.4 | 1.05 ± 0.32 |
| lanjian | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.5 | 1.07 ± 0.32 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.2 | 1.3 | 1.07 ± 0.33 |
| mattcl | input-mattcl | 0.9 ± 0.1 | 0.5 | 1.1 | 1.07 ± 0.31 |
| lanjian | input-kcen | 0.9 ± 0.1 | 0.3 | 1.1 | 1.08 ± 0.31 |
| mattcl | input-kcen | 0.9 ± 0.1 | 0.2 | 1.5 | 1.11 ± 0.31 |
| mattcl-ts | input-kcen | 9.7 ± 0.4 | 8.6 | 10.9 | 11.67 ± 2.93 |
| mattcl-ts | input-lanjian | 9.7 ± 0.3 | 8.7 | 10.5 | 11.70 ± 2.92 |
| mattcl-ts | input-mattcl | 9.7 ± 0.4 | 8.6 | 10.7 | 11.72 ± 2.94 |
| mattcl-ts | input-pting | 9.7 ± 0.3 | 8.5 | 10.5 | 11.75 ± 2.94 |
| kcen | input-mattcl | 14.2 ± 0.4 | 13.3 | 16.8 | 17.17 ± 4.28 |
| mattcl-py | input-pting | 14.2 ± 0.6 | 13.4 | 17.5 | 17.19 ± 4.31 |
| kcen | input-pting | 14.2 ± 0.6 | 13.3 | 17.6 | 17.19 ± 4.31 |
| pting | input-pting | 14.3 ± 0.5 | 13.5 | 17.1 | 17.22 ± 4.31 |
| pting | input-mattcl | 14.3 ± 0.6 | 13.3 | 17.4 | 17.23 ± 4.33 |
| pting | input-lanjian | 14.3 ± 0.7 | 13.2 | 18.0 | 17.23 ± 4.35 |
| mattcl-py | input-lanjian | 14.3 ± 0.7 | 13.0 | 17.4 | 17.24 ± 4.35 |
| mattcl-py | input-mattcl | 14.3 ± 0.7 | 13.4 | 18.0 | 17.26 ± 4.35 |
| pting | input-kcen | 14.3 ± 0.6 | 13.4 | 18.2 | 17.32 ± 4.36 |
| kcen | input-lanjian | 14.3 ± 0.6 | 13.3 | 17.8 | 17.32 ± 4.35 |
| kcen | input-kcen | 14.3 ± 0.6 | 13.4 | 17.8 | 17.33 ± 4.35 |
| mattcl-py | input-kcen | 14.5 ± 2.2 | 13.4 | 44.7 | 17.48 ± 5.09 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|