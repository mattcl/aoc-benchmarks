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
| lanjian | input-lanjian | 0.7 ± 0.2 | 0.0 | 1.0 | 1.00 |
| mattcl | input-pting | 0.7 ± 0.2 | 0.0 | 0.9 | 1.03 ± 0.43 |
| mattcl | input-kcen | 0.7 ± 0.2 | 0.0 | 0.9 | 1.03 ± 0.44 |
| lanjian | input-kcen | 0.7 ± 0.2 | 0.1 | 1.0 | 1.04 ± 0.41 |
| mattcl | input-lanjian | 0.7 ± 0.2 | 0.0 | 1.1 | 1.07 ± 0.42 |
| lanjian | input-pting | 0.7 ± 0.2 | 0.1 | 1.5 | 1.07 ± 0.42 |
| lanjian | input-mattcl | 0.7 ± 0.2 | 0.1 | 1.4 | 1.07 ± 0.42 |
| mattcl | input-mattcl | 0.7 ± 0.2 | 0.1 | 1.1 | 1.08 ± 0.42 |
| mattcl-ts | input-pting | 9.6 ± 0.4 | 8.5 | 10.7 | 14.20 ± 4.42 |
| mattcl-ts | input-kcen | 9.7 ± 0.4 | 8.8 | 11.0 | 14.24 ± 4.42 |
| mattcl-ts | input-mattcl | 9.7 ± 0.3 | 8.6 | 10.5 | 14.25 ± 4.42 |
| mattcl-ts | input-lanjian | 9.8 ± 2.1 | 8.5 | 39.5 | 14.45 ± 5.46 |
| mattcl-py | input-mattcl | 13.9 ± 0.4 | 13.1 | 16.9 | 20.40 ± 6.32 |
| pting | input-mattcl | 13.9 ± 0.4 | 13.0 | 16.5 | 20.43 ± 6.33 |
| mattcl-py | input-lanjian | 13.9 ± 0.5 | 13.0 | 17.0 | 20.49 ± 6.36 |
| pting | input-lanjian | 13.9 ± 0.6 | 13.0 | 17.5 | 20.51 ± 6.39 |
| kcen | input-mattcl | 13.9 ± 0.6 | 13.1 | 16.7 | 20.52 ± 6.38 |
| mattcl-py | input-pting | 13.9 ± 0.6 | 13.2 | 16.9 | 20.52 ± 6.39 |
| kcen | input-kcen | 13.9 ± 0.5 | 12.9 | 17.0 | 20.52 ± 6.37 |
| pting | input-kcen | 13.9 ± 0.6 | 12.9 | 17.6 | 20.53 ± 6.39 |
| pting | input-pting | 13.9 ± 0.6 | 13.0 | 16.8 | 20.55 ± 6.39 |
| mattcl-py | input-kcen | 14.0 ± 0.6 | 12.9 | 17.1 | 20.55 ± 6.39 |
| kcen | input-pting | 14.0 ± 0.5 | 13.0 | 16.5 | 20.58 ± 6.39 |
| kcen | input-lanjian | 14.0 ± 0.7 | 12.9 | 17.3 | 20.59 ± 6.43 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|