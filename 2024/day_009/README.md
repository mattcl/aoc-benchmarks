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
| mattcl | input-kcen | 2.3 ± 0.3 | 1.5 | 3.2 | 1.00 |
| mattcl | input-mattcl | 2.3 ± 0.4 | 1.5 | 3.6 | 1.01 ± 0.22 |
| mattcl | input-lanjian | 2.4 ± 0.3 | 1.3 | 3.9 | 1.03 ± 0.22 |
| lanjian | input-mattcl | 2.6 ± 0.3 | 1.7 | 4.6 | 1.12 ± 0.22 |
| lanjian | input-kcen | 2.6 ± 0.2 | 1.8 | 3.3 | 1.13 ± 0.20 |
| lanjian | input-lanjian | 2.6 ± 0.3 | 1.5 | 3.9 | 1.13 ± 0.21 |
| kcen | input-lanjian | 3.9 ± 0.4 | 3.1 | 6.8 | 1.71 ± 0.32 |
| kcen | input-kcen | 4.1 ± 0.4 | 3.5 | 7.2 | 1.76 ± 0.32 |
| kcen | input-mattcl | 4.1 ± 0.5 | 3.2 | 7.3 | 1.79 ± 0.35 |
| mattcl-py | input-lanjian | 31.6 ± 0.8 | 30.5 | 34.9 | 13.74 ± 2.11 |
| mattcl-py | input-mattcl | 31.7 ± 0.7 | 30.3 | 34.1 | 13.76 ± 2.11 |
| mattcl-py | input-kcen | 31.9 ± 1.1 | 30.3 | 35.0 | 13.88 ± 2.16 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6378826667552</pre>|<pre>6413328569890</pre>|
|input-lanjian|<pre>6401092019345</pre>|<pre>6431472344710</pre>|
|input-mattcl|<pre>6349606724455</pre>|<pre>6376648986651</pre>|