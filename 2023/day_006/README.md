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
| lanjian | input-pting | 0.7 ± 0.2 | 0.0 | 0.9 | 1.04 ± 0.40 |
| mattcl | input-mattcl | 0.7 ± 0.2 | 0.0 | 1.5 | 1.04 ± 0.44 |
| lanjian | input-kcen | 0.7 ± 0.2 | 0.0 | 1.4 | 1.05 ± 0.41 |
| mattcl | input-lanjian | 0.7 ± 0.2 | 0.0 | 1.0 | 1.07 ± 0.42 |
| mattcl | input-kcen | 0.7 ± 0.2 | 0.2 | 1.3 | 1.07 ± 0.42 |
| mattcl | input-pting | 0.7 ± 0.2 | 0.0 | 1.0 | 1.08 ± 0.41 |
| lanjian | input-lanjian | 0.7 ± 0.1 | 0.1 | 0.9 | 1.08 ± 0.38 |
| mattcl-ts | input-pting | 9.4 ± 0.4 | 8.3 | 10.3 | 14.13 ± 4.35 |
| mattcl-ts | input-lanjian | 9.5 ± 0.4 | 8.4 | 10.3 | 14.23 ± 4.38 |
| mattcl-ts | input-kcen | 9.5 ± 0.4 | 8.5 | 10.6 | 14.25 ± 4.39 |
| mattcl-ts | input-mattcl | 9.7 ± 0.8 | 8.7 | 12.1 | 14.58 ± 4.60 |
| pting | input-kcen | 14.0 ± 0.6 | 13.0 | 17.4 | 21.03 ± 6.49 |
| mattcl-py | input-lanjian | 14.1 ± 0.5 | 13.3 | 17.6 | 21.05 ± 6.48 |
| pting | input-pting | 14.1 ± 0.6 | 13.2 | 17.9 | 21.08 ± 6.51 |
| mattcl-py | input-pting | 14.1 ± 0.7 | 12.9 | 17.6 | 21.09 ± 6.52 |
| pting | input-lanjian | 14.1 ± 0.6 | 12.9 | 17.4 | 21.09 ± 6.51 |
| kcen | input-mattcl | 14.1 ± 0.6 | 13.2 | 17.4 | 21.18 ± 6.53 |
| kcen | input-lanjian | 14.2 ± 0.7 | 12.9 | 17.5 | 21.23 ± 6.57 |
| kcen | input-kcen | 14.2 ± 0.7 | 13.0 | 17.4 | 21.23 ± 6.59 |
| mattcl-py | input-mattcl | 14.2 ± 0.7 | 12.9 | 17.5 | 21.23 ± 6.57 |
| pting | input-mattcl | 14.3 ± 2.7 | 12.9 | 51.4 | 21.41 ± 7.68 |
| mattcl-py | input-kcen | 14.3 ± 1.9 | 13.2 | 40.3 | 21.49 ± 7.18 |
| kcen | input-pting | 14.5 ± 3.4 | 13.0 | 47.3 | 21.65 ± 8.31 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|