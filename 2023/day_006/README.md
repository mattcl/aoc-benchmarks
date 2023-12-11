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
| lanjian | input-pting | 0.7 ± 0.2 | 0.0 | 1.0 | 1.00 |
| lanjian | input-kcen | 0.7 ± 0.2 | 0.0 | 1.1 | 1.09 ± 0.44 |
| mattcl | input-kcen | 0.7 ± 0.2 | 0.0 | 1.3 | 1.10 ± 0.46 |
| lanjian | input-mattcl | 0.7 ± 0.2 | 0.1 | 0.9 | 1.10 ± 0.42 |
| mattcl | input-pting | 0.7 ± 0.2 | 0.0 | 1.4 | 1.10 ± 0.46 |
| lanjian | input-lanjian | 0.7 ± 0.1 | 0.1 | 1.3 | 1.11 ± 0.42 |
| mattcl | input-lanjian | 0.7 ± 0.2 | 0.1 | 1.2 | 1.12 ± 0.44 |
| mattcl | input-mattcl | 0.7 ± 0.1 | 0.3 | 1.4 | 1.14 ± 0.42 |
| mattcl-ts | input-mattcl | 10.0 ± 0.3 | 9.0 | 11.6 | 15.13 ± 4.84 |
| mattcl-ts | input-pting | 10.0 ± 0.3 | 8.9 | 11.3 | 15.18 ± 4.85 |
| mattcl-ts | input-lanjian | 10.0 ± 0.3 | 9.2 | 11.1 | 15.22 ± 4.86 |
| mattcl-ts | input-kcen | 10.2 ± 1.7 | 9.1 | 34.3 | 15.42 ± 5.56 |
| pting | input-kcen | 14.1 ± 0.6 | 13.1 | 16.9 | 21.33 ± 6.83 |
| kcen | input-lanjian | 14.1 ± 0.6 | 12.9 | 17.0 | 21.34 ± 6.84 |
| mattcl-py | input-kcen | 14.1 ± 0.7 | 13.0 | 17.4 | 21.44 ± 6.89 |
| pting | input-pting | 14.1 ± 0.6 | 12.9 | 17.5 | 21.45 ± 6.88 |
| mattcl-py | input-pting | 14.2 ± 0.6 | 13.2 | 16.8 | 21.48 ± 6.88 |
| pting | input-lanjian | 14.2 ± 0.7 | 12.9 | 17.3 | 21.49 ± 6.91 |
| kcen | input-kcen | 14.2 ± 0.6 | 13.0 | 17.2 | 21.49 ± 6.90 |
| pting | input-mattcl | 14.2 ± 0.7 | 13.2 | 18.3 | 21.54 ± 6.93 |
| kcen | input-mattcl | 14.2 ± 0.7 | 12.9 | 17.2 | 21.54 ± 6.92 |
| kcen | input-pting | 14.2 ± 0.7 | 13.3 | 17.7 | 21.55 ± 6.92 |
| mattcl-py | input-lanjian | 14.3 ± 2.3 | 13.1 | 45.8 | 21.63 ± 7.71 |
| mattcl-py | input-mattcl | 14.5 ± 3.6 | 13.1 | 64.0 | 21.96 ± 8.85 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|