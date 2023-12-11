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

- [chancalan](https://github.com/chancalan/aoc2023) (python)
- [kcen](https://github.com/kcen/aoc2023) (python)
- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [mattcl-ts](https://github.com/mattcl/aoc2023-js) (typescript (bun))
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| lanjian | input-pting | 0.8 ± 0.2 | 0.2 | 1.1 | 1.00 |
| lanjian | input-kcen | 0.9 ± 0.2 | 0.2 | 1.1 | 1.04 ± 0.31 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.2 | 1.1 | 1.06 ± 0.32 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.2 | 1.1 | 1.07 ± 0.31 |
| lanjian | input-lanjian | 0.9 ± 0.2 | 0.2 | 1.1 | 1.07 ± 0.32 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.2 | 1.7 | 1.08 ± 0.34 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.3 | 1.3 | 1.08 ± 0.32 |
| lanjian | input-mattcl | 0.9 ± 0.1 | 0.4 | 1.4 | 1.13 ± 0.29 |
| mattcl-ts | input-lanjian | 9.6 ± 0.4 | 8.7 | 10.7 | 11.64 ± 2.77 |
| mattcl-ts | input-mattcl | 9.6 ± 0.4 | 8.6 | 10.4 | 11.67 ± 2.77 |
| mattcl-ts | input-pting | 9.6 ± 0.4 | 8.7 | 10.9 | 11.69 ± 2.78 |
| mattcl-ts | input-kcen | 9.6 ± 0.4 | 8.6 | 10.6 | 11.74 ± 2.79 |
| chancalan | input-lanjian | 14.0 ± 0.5 | 12.9 | 16.7 | 17.07 ± 4.05 |
| kcen | input-pting | 14.0 ± 0.4 | 13.2 | 16.2 | 17.07 ± 4.04 |
| chancalan | input-pting | 14.0 ± 0.5 | 13.1 | 17.3 | 17.11 ± 4.07 |
| mattcl-py | input-lanjian | 14.0 ± 0.4 | 13.1 | 16.1 | 17.11 ± 4.04 |
| pting | input-pting | 14.1 ± 0.5 | 13.2 | 17.5 | 17.12 ± 4.06 |
| mattcl-py | input-pting | 14.1 ± 0.5 | 13.1 | 17.2 | 17.12 ± 4.06 |
| kcen | input-mattcl | 14.1 ± 0.6 | 13.0 | 17.5 | 17.16 ± 4.10 |
| kcen | input-kcen | 14.1 ± 0.6 | 13.0 | 17.6 | 17.16 ± 4.09 |
| chancalan | input-mattcl | 14.1 ± 0.6 | 13.1 | 17.3 | 17.18 ± 4.11 |
| chancalan | input-kcen | 14.1 ± 0.6 | 13.3 | 17.8 | 17.20 ± 4.10 |
| kcen | input-lanjian | 14.1 ± 0.6 | 13.0 | 17.5 | 17.20 ± 4.11 |
| pting | input-lanjian | 14.1 ± 0.6 | 13.2 | 17.3 | 17.22 ± 4.10 |
| pting | input-kcen | 14.2 ± 0.8 | 13.1 | 17.6 | 17.32 ± 4.17 |
| pting | input-mattcl | 14.3 ± 2.4 | 13.2 | 48.0 | 17.38 ± 5.05 |
| mattcl-py | input-mattcl | 14.3 ± 2.3 | 12.9 | 45.9 | 17.38 ± 4.97 |
| mattcl-py | input-kcen | 14.3 ± 2.9 | 13.1 | 54.7 | 17.45 ± 5.44 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|