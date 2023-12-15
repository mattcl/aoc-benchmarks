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
| mattcl | input-pting | 0.9 ± 0.2 | 0.6 | 1.5 | 1.00 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.6 | 1.5 | 1.00 ± 0.31 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.6 | 1.4 | 1.02 ± 0.30 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.7 | 1.8 | 1.19 ± 0.35 |
| lanjian | input-pting | 1.1 ± 0.2 | 0.7 | 1.7 | 1.19 ± 0.35 |
| lanjian | input-lanjian | 1.1 ± 0.2 | 0.7 | 1.7 | 1.19 ± 0.35 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.7 | 1.8 | 1.19 ± 0.36 |
| mattcl | input-mattcl | 1.2 ± 3.5 | 0.6 | 50.7 | 1.26 ± 3.80 |
| mattcl-py | input-kcen | 15.8 ± 0.6 | 14.9 | 18.6 | 17.01 ± 3.58 |
| mattcl-py | input-lanjian | 15.9 ± 0.6 | 14.8 | 19.0 | 17.10 ± 3.60 |
| mattcl-py | input-mattcl | 16.0 ± 0.6 | 14.8 | 19.7 | 17.15 ± 3.61 |
| mattcl-py | input-pting | 16.1 ± 0.7 | 15.0 | 18.8 | 17.33 ± 3.66 |
| pting | input-lanjian | 17.0 ± 0.6 | 16.0 | 20.0 | 18.26 ± 3.83 |
| pting | input-pting | 17.1 ± 0.6 | 16.3 | 20.5 | 18.41 ± 3.85 |
| pting | input-kcen | 17.1 ± 0.7 | 16.2 | 20.3 | 18.43 ± 3.88 |
| pting | input-mattcl | 17.1 ± 0.6 | 16.2 | 20.0 | 18.43 ± 3.87 |
| kcen | input-lanjian | 20.3 ± 0.6 | 18.9 | 22.5 | 21.78 ± 4.55 |
| kcen | input-kcen | 20.3 ± 0.7 | 19.3 | 23.1 | 21.80 ± 4.57 |
| kcen | input-pting | 20.6 ± 0.8 | 19.3 | 23.2 | 22.10 ± 4.64 |
| kcen | input-mattcl | 20.6 ± 0.8 | 19.5 | 27.4 | 22.17 ± 4.66 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|