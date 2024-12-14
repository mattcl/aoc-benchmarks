# Day 9 benchmarks

[link to problem](https://adventofcode.com/2024/day/9)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2024)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 9)

- [kcen](https://github.com/kcen/aoc2024) (nim)
- [lanjian](https://github.com/lanjian/aoc-2024) (rust)
- [mattcl](https://github.com/mattcl/aoc2024) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2024-py) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-lanjian | 2.1 ± 0.3 | 1.5 | 3.9 | 1.00 |
| mattcl | input-kcen | 2.1 ± 0.3 | 1.2 | 2.9 | 1.01 ± 0.22 |
| mattcl | input-mattcl | 2.1 ± 0.4 | 1.4 | 3.6 | 1.01 ± 0.24 |
| lanjian | input-mattcl | 2.4 ± 0.4 | 1.1 | 4.3 | 1.12 ± 0.26 |
| lanjian | input-lanjian | 2.4 ± 0.3 | 1.6 | 3.0 | 1.14 ± 0.22 |
| lanjian | input-kcen | 2.4 ± 0.3 | 1.4 | 4.0 | 1.14 ± 0.24 |
| kcen | input-lanjian | 4.5 ± 0.6 | 3.9 | 7.5 | 2.13 ± 0.43 |
| kcen | input-mattcl | 4.6 ± 0.4 | 3.7 | 6.2 | 2.18 ± 0.41 |
| kcen | input-kcen | 4.7 ± 0.4 | 3.8 | 7.6 | 2.24 ± 0.40 |
| mattcl-py | input-kcen | 31.3 ± 0.8 | 30.0 | 34.4 | 14.89 ± 2.41 |
| mattcl-py | input-lanjian | 31.4 ± 0.8 | 30.2 | 34.9 | 14.94 ± 2.42 |
| mattcl-py | input-mattcl | 31.5 ± 1.1 | 30.0 | 35.1 | 14.99 ± 2.45 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6378826667552</pre>|<pre>6413328569890</pre>|
|input-lanjian|<pre>6401092019345</pre>|<pre>6431472344710</pre>|
|input-mattcl|<pre>6349606724455</pre>|<pre>6376648986651</pre>|