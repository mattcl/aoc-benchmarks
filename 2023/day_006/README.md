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
| lanjian | input-kcen | 0.7 ± 0.2 | 0.1 | 1.1 | 1.00 |
| mattcl | input-lanjian | 0.7 ± 0.2 | 0.0 | 1.0 | 1.01 ± 0.41 |
| mattcl | input-mattcl | 0.7 ± 0.2 | 0.0 | 1.1 | 1.01 ± 0.39 |
| lanjian | input-mattcl | 0.7 ± 0.2 | 0.1 | 1.0 | 1.03 ± 0.37 |
| mattcl | input-pting | 0.7 ± 0.2 | 0.1 | 0.9 | 1.03 ± 0.39 |
| lanjian | input-pting | 0.7 ± 0.1 | 0.1 | 1.0 | 1.05 ± 0.35 |
| lanjian | input-lanjian | 0.7 ± 0.2 | 0.0 | 1.4 | 1.07 ± 0.37 |
| mattcl | input-kcen | 0.7 ± 0.2 | 0.0 | 1.4 | 1.07 ± 0.38 |
| mattcl-ts | input-mattcl | 9.9 ± 0.3 | 9.0 | 11.1 | 14.35 ± 3.92 |
| mattcl-ts | input-kcen | 9.9 ± 0.3 | 9.0 | 10.7 | 14.37 ± 3.92 |
| mattcl-ts | input-lanjian | 9.9 ± 0.3 | 8.9 | 11.2 | 14.38 ± 3.92 |
| mattcl-ts | input-pting | 9.9 ± 0.3 | 8.9 | 10.9 | 14.38 ± 3.92 |
| mattcl-py | input-mattcl | 13.9 ± 0.4 | 13.2 | 17.7 | 20.14 ± 5.49 |
| kcen | input-pting | 14.0 ± 0.5 | 12.9 | 17.3 | 20.23 ± 5.53 |
| pting | input-pting | 14.1 ± 0.4 | 13.2 | 17.2 | 20.32 ± 5.54 |
| mattcl-py | input-kcen | 14.1 ± 0.7 | 13.1 | 17.2 | 20.34 ± 5.59 |
| pting | input-kcen | 14.1 ± 0.6 | 13.2 | 17.7 | 20.37 ± 5.58 |
| mattcl-py | input-lanjian | 14.1 ± 0.6 | 12.9 | 17.4 | 20.41 ± 5.60 |
| kcen | input-mattcl | 14.1 ± 0.6 | 12.8 | 17.2 | 20.42 ± 5.60 |
| kcen | input-kcen | 14.1 ± 0.5 | 13.3 | 16.7 | 20.44 ± 5.59 |
| pting | input-mattcl | 14.2 ± 0.6 | 13.3 | 17.4 | 20.47 ± 5.60 |
| mattcl-py | input-pting | 14.2 ± 0.7 | 13.1 | 17.8 | 20.51 ± 5.64 |
| kcen | input-lanjian | 14.2 ± 0.6 | 13.4 | 17.4 | 20.53 ± 5.62 |
| pting | input-lanjian | 14.5 ± 4.0 | 13.0 | 55.2 | 20.97 ± 8.12 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|