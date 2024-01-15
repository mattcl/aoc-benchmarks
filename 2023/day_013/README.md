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
| mattcl | input-kcen | 0.9 ± 0.2 | 0.5 | 1.5 | 1.00 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.5 | 1.4 | 1.00 ± 0.32 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.5 | 1.6 | 1.01 ± 0.34 |
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.5 | 1.4 | 1.04 ± 0.33 |
| lanjian | input-lanjian | 1.0 ± 0.2 | 0.6 | 1.6 | 1.13 ± 0.36 |
| lanjian | input-pting | 1.0 ± 0.2 | 0.6 | 1.6 | 1.17 ± 0.39 |
| lanjian | input-mattcl | 1.0 ± 0.2 | 0.6 | 1.7 | 1.17 ± 0.39 |
| lanjian | input-kcen | 1.0 ± 0.2 | 0.7 | 1.6 | 1.18 ± 0.37 |
| mattcl-py | input-kcen | 15.4 ± 0.5 | 14.4 | 18.4 | 17.78 ± 4.16 |
| mattcl-py | input-lanjian | 15.4 ± 0.6 | 14.6 | 18.3 | 17.81 ± 4.18 |
| mattcl-py | input-pting | 15.5 ± 0.7 | 14.4 | 18.7 | 17.88 ± 4.21 |
| mattcl-py | input-mattcl | 15.5 ± 0.6 | 14.6 | 18.6 | 17.96 ± 4.22 |
| pting | input-lanjian | 16.5 ± 0.6 | 15.7 | 19.3 | 19.10 ± 4.47 |
| pting | input-kcen | 16.5 ± 0.6 | 15.9 | 19.3 | 19.13 ± 4.48 |
| pting | input-pting | 16.6 ± 0.6 | 15.6 | 19.6 | 19.26 ± 4.51 |
| pting | input-mattcl | 16.7 ± 0.6 | 15.5 | 20.3 | 19.35 ± 4.54 |
| kcen | input-lanjian | 19.7 ± 0.6 | 18.6 | 22.7 | 22.84 ± 5.33 |
| kcen | input-kcen | 19.8 ± 0.6 | 18.4 | 22.3 | 22.88 ± 5.34 |
| kcen | input-mattcl | 20.0 ± 0.6 | 18.8 | 22.2 | 23.15 ± 5.40 |
| kcen | input-pting | 20.1 ± 0.7 | 19.1 | 22.8 | 23.20 ± 5.43 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|