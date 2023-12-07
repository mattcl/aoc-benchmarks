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
| lanjian | input-kcen | 0.7 ± 0.2 | 0.1 | 0.9 | 1.00 |
| mattcl | input-lanjian | 0.7 ± 0.2 | 0.0 | 0.9 | 1.02 ± 0.47 |
| lanjian | input-pting | 0.7 ± 0.2 | 0.0 | 1.2 | 1.02 ± 0.43 |
| mattcl | input-mattcl | 0.7 ± 0.2 | 0.0 | 1.1 | 1.03 ± 0.46 |
| lanjian | input-mattcl | 0.7 ± 0.2 | 0.1 | 1.1 | 1.07 ± 0.44 |
| mattcl | input-kcen | 0.7 ± 0.2 | 0.1 | 1.4 | 1.10 ± 0.45 |
| mattcl | input-pting | 0.7 ± 0.2 | 0.1 | 1.1 | 1.10 ± 0.43 |
| lanjian | input-lanjian | 0.7 ± 0.1 | 0.3 | 0.9 | 1.12 ± 0.39 |
| mattcl-ts | input-kcen | 9.2 ± 0.3 | 8.0 | 9.9 | 14.08 ± 4.51 |
| mattcl-ts | input-mattcl | 9.2 ± 0.4 | 8.1 | 10.8 | 14.09 ± 4.52 |
| mattcl-ts | input-lanjian | 9.2 ± 0.3 | 8.0 | 10.1 | 14.09 ± 4.51 |
| mattcl-ts | input-pting | 9.2 ± 0.3 | 8.2 | 9.9 | 14.12 ± 4.52 |
| mattcl-py | input-mattcl | 13.9 ± 0.4 | 12.8 | 16.8 | 21.30 ± 6.81 |
| pting | input-lanjian | 13.9 ± 0.5 | 13.0 | 16.9 | 21.35 ± 6.84 |
| mattcl-py | input-kcen | 13.9 ± 0.5 | 13.2 | 16.8 | 21.36 ± 6.85 |
| kcen | input-kcen | 13.9 ± 0.6 | 13.0 | 17.6 | 21.38 ± 6.86 |
| mattcl-py | input-lanjian | 14.0 ± 0.6 | 13.0 | 17.9 | 21.40 ± 6.88 |
| pting | input-pting | 14.0 ± 0.6 | 12.9 | 17.6 | 21.41 ± 6.87 |
| pting | input-kcen | 14.0 ± 0.6 | 13.0 | 16.8 | 21.41 ± 6.87 |
| kcen | input-mattcl | 14.0 ± 0.7 | 13.1 | 17.4 | 21.41 ± 6.89 |
| pting | input-mattcl | 14.0 ± 0.6 | 12.9 | 17.2 | 21.42 ± 6.88 |
| mattcl-py | input-pting | 14.0 ± 0.7 | 13.0 | 17.7 | 21.47 ± 6.91 |
| kcen | input-pting | 14.0 ± 0.7 | 13.0 | 17.8 | 21.47 ± 6.90 |
| kcen | input-lanjian | 14.3 ± 3.2 | 13.0 | 46.2 | 21.89 ± 8.56 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>840336</pre>|<pre>41382569</pre>|
|input-lanjian|<pre>114400</pre>|<pre>21039729</pre>|
|input-mattcl|<pre>1312850</pre>|<pre>36749103</pre>|
|input-pting|<pre>2756160</pre>|<pre>34788142</pre>|