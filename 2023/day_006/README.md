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
| lanjian | input-kcen | 0.8 ± 0.2 | 0.1 | 1.1 | 1.08 ± 0.43 |
| lanjian | input-pting | 0.8 ± 0.2 | 0.1 | 1.0 | 1.09 ± 0.43 |
| mattcl | input-kcen | 0.8 ± 0.2 | 0.1 | 1.4 | 1.09 ± 0.44 |
| mattcl | input-mattcl | 0.8 ± 0.2 | 0.1 | 1.0 | 1.09 ± 0.44 |
| lanjian | input-lanjian | 0.8 ± 0.2 | 0.1 | 1.0 | 1.10 ± 0.42 |
| mattcl | input-lanjian | 0.8 ± 0.2 | 0.2 | 1.0 | 1.12 ± 0.43 |
| mattcl | input-pting | 0.8 ± 0.2 | 0.3 | 1.5 | 1.13 ± 0.44 |
| mattcl-ts | input-pting | 9.2 ± 0.4 | 8.2 | 10.2 | 13.31 ± 4.40 |
| mattcl-ts | input-kcen | 9.2 ± 0.3 | 8.2 | 10.3 | 13.31 ± 4.40 |
| mattcl-ts | input-mattcl | 9.2 ± 0.3 | 8.4 | 10.1 | 13.33 ± 4.40 |
| mattcl-ts | input-lanjian | 9.3 ± 0.3 | 8.3 | 10.4 | 13.39 ± 4.42 |
| pting | input-mattcl | 13.9 ± 0.4 | 13.0 | 16.9 | 20.03 ± 6.60 |
| pting | input-kcen | 13.9 ± 0.4 | 13.0 | 16.2 | 20.05 ± 6.60 |
| pting | input-pting | 13.9 ± 0.4 | 12.8 | 16.5 | 20.06 ± 6.62 |
| mattcl-py | input-kcen | 13.9 ± 0.5 | 12.9 | 17.1 | 20.08 ± 6.63 |
| mattcl-py | input-pting | 13.9 ± 0.5 | 13.1 | 16.7 | 20.13 ± 6.65 |
| kcen | input-mattcl | 14.0 ± 0.5 | 13.0 | 17.2 | 20.13 ± 6.65 |
| mattcl-py | input-mattcl | 14.0 ± 0.6 | 13.0 | 16.9 | 20.16 ± 6.67 |
| kcen | input-pting | 14.0 ± 0.6 | 13.0 | 17.4 | 20.16 ± 6.67 |
| mattcl-py | input-lanjian | 14.0 ± 0.6 | 12.9 | 17.0 | 20.20 ± 6.69 |
| kcen | input-lanjian | 14.0 ± 0.6 | 12.8 | 17.4 | 20.20 ± 6.70 |
| pting | input-lanjian | 14.1 ± 1.3 | 13.2 | 31.2 | 20.33 ± 6.93 |
| kcen | input-kcen | 14.2 ± 0.8 | 13.4 | 18.2 | 20.49 ± 6.83 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|