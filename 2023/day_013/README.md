# Day 13 benchmarks

[link to problem](https://adventofcode.com/2023/day/13)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 13)

- [kcen](https://github.com/kcen/aoc2023) (python)
- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-pting | 0.9 ± 0.2 | 0.6 | 1.4 | 1.00 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.6 | 1.5 | 1.04 ± 0.33 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.6 | 1.5 | 1.04 ± 0.33 |
| mattcl | input-lanjian | 1.0 ± 0.2 | 0.6 | 1.5 | 1.06 ± 0.35 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.7 | 1.7 | 1.13 ± 0.36 |
| lanjian | input-pting | 1.1 ± 0.2 | 0.7 | 1.7 | 1.16 ± 0.35 |
| lanjian | input-mattcl | 1.1 ± 0.3 | 0.7 | 1.7 | 1.16 ± 0.37 |
| lanjian | input-lanjian | 1.1 ± 0.3 | 0.7 | 1.7 | 1.18 ± 0.37 |
| mattcl-py | input-lanjian | 15.7 ± 0.6 | 14.5 | 18.9 | 17.31 ± 3.78 |
| mattcl-py | input-kcen | 15.8 ± 0.7 | 15.0 | 19.1 | 17.43 ± 3.83 |
| mattcl-py | input-mattcl | 15.9 ± 0.7 | 14.5 | 18.6 | 17.48 ± 3.83 |
| mattcl-py | input-pting | 15.9 ± 0.7 | 15.0 | 18.9 | 17.53 ± 3.84 |
| pting | input-lanjian | 16.8 ± 0.8 | 16.0 | 20.6 | 18.53 ± 4.07 |
| pting | input-kcen | 16.9 ± 0.8 | 15.9 | 20.7 | 18.64 ± 4.10 |
| pting | input-mattcl | 17.1 ± 0.7 | 16.0 | 20.3 | 18.82 ± 4.11 |
| pting | input-pting | 17.2 ± 0.7 | 16.0 | 20.5 | 18.88 ± 4.13 |
| kcen | input-lanjian | 20.1 ± 0.6 | 18.8 | 22.7 | 22.10 ± 4.80 |
| kcen | input-kcen | 20.1 ± 0.7 | 18.8 | 23.1 | 22.15 ± 4.83 |
| kcen | input-pting | 20.3 ± 0.6 | 19.3 | 23.5 | 22.32 ± 4.85 |
| kcen | input-mattcl | 20.6 ± 0.9 | 19.0 | 23.8 | 22.62 ± 4.96 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|