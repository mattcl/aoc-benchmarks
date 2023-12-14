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
| mattcl | input-lanjian | 0.9 ± 0.2 | 0.6 | 1.4 | 1.00 |
| mattcl | input-mattcl | 0.9 ± 0.2 | 0.6 | 1.5 | 1.01 ± 0.34 |
| mattcl | input-kcen | 0.9 ± 0.2 | 0.6 | 1.4 | 1.01 ± 0.33 |
| mattcl | input-pting | 0.9 ± 0.2 | 0.6 | 1.4 | 1.02 ± 0.34 |
| lanjian | input-pting | 1.0 ± 0.2 | 0.7 | 1.8 | 1.16 ± 0.37 |
| lanjian | input-kcen | 1.1 ± 0.2 | 0.7 | 1.7 | 1.17 ± 0.39 |
| lanjian | input-lanjian | 1.1 ± 0.3 | 0.7 | 1.6 | 1.17 ± 0.39 |
| lanjian | input-mattcl | 1.1 ± 0.2 | 0.7 | 1.6 | 1.18 ± 0.38 |
| mattcl-py | input-lanjian | 15.7 ± 0.7 | 14.4 | 18.7 | 17.35 ± 4.14 |
| mattcl-py | input-pting | 15.7 ± 0.7 | 14.7 | 19.3 | 17.36 ± 4.15 |
| mattcl-py | input-mattcl | 15.7 ± 0.7 | 14.6 | 19.0 | 17.39 ± 4.15 |
| mattcl-py | input-kcen | 15.8 ± 2.6 | 14.7 | 49.7 | 17.48 ± 4.99 |
| pting | input-kcen | 16.7 ± 0.5 | 15.9 | 19.0 | 18.47 ± 4.37 |
| pting | input-pting | 16.9 ± 0.7 | 16.1 | 20.5 | 18.64 ± 4.43 |
| pting | input-lanjian | 16.9 ± 2.1 | 15.6 | 42.2 | 18.67 ± 4.93 |
| pting | input-mattcl | 17.0 ± 0.7 | 15.9 | 19.8 | 18.75 ± 4.46 |
| kcen | input-lanjian | 20.1 ± 0.7 | 18.9 | 22.8 | 22.17 ± 5.26 |
| kcen | input-kcen | 20.1 ± 0.6 | 19.0 | 22.9 | 22.20 ± 5.26 |
| kcen | input-pting | 20.2 ± 0.5 | 19.3 | 22.2 | 22.30 ± 5.26 |
| kcen | input-mattcl | 20.4 ± 0.6 | 19.6 | 22.9 | 22.58 ± 5.34 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>35538</pre>|<pre>30442</pre>|
|input-lanjian|<pre>35691</pre>|<pre>39037</pre>|
|input-mattcl|<pre>31739</pre>|<pre>31539</pre>|
|input-pting|<pre>41859</pre>|<pre>30842</pre>|