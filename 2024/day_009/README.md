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
| mattcl | input-lanjian | 2.2 ± 0.3 | 1.3 | 2.9 | 1.00 |
| mattcl | input-kcen | 2.2 ± 0.4 | 1.2 | 3.6 | 1.00 ± 0.23 |
| mattcl | input-mattcl | 2.2 ± 0.4 | 1.3 | 4.7 | 1.04 ± 0.23 |
| lanjian | input-mattcl | 2.5 ± 0.3 | 1.4 | 3.7 | 1.15 ± 0.22 |
| lanjian | input-kcen | 2.5 ± 0.2 | 1.9 | 3.5 | 1.16 ± 0.21 |
| lanjian | input-lanjian | 2.6 ± 0.3 | 1.6 | 3.4 | 1.19 ± 0.22 |
| kcen | input-lanjian | 3.8 ± 0.4 | 2.9 | 7.1 | 1.78 ± 0.32 |
| kcen | input-mattcl | 3.9 ± 0.4 | 3.1 | 7.1 | 1.81 ± 0.34 |
| kcen | input-kcen | 3.9 ± 0.5 | 3.2 | 8.0 | 1.82 ± 0.35 |
| mattcl-py | input-mattcl | 31.7 ± 0.7 | 30.5 | 34.2 | 14.68 ± 2.22 |
| mattcl-py | input-kcen | 31.7 ± 0.7 | 30.7 | 34.5 | 14.68 ± 2.23 |
| mattcl-py | input-lanjian | 31.7 ± 0.7 | 30.1 | 34.7 | 14.70 ± 2.23 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6378826667552</pre>|<pre>6413328569890</pre>|
|input-lanjian|<pre>6401092019345</pre>|<pre>6431472344710</pre>|
|input-mattcl|<pre>6349606724455</pre>|<pre>6376648986651</pre>|