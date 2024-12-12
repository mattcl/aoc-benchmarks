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
| mattcl | input-kcen | 2.1 ± 0.3 | 1.4 | 3.1 | 1.00 |
| mattcl | input-mattcl | 2.1 ± 0.3 | 1.3 | 2.9 | 1.01 ± 0.23 |
| mattcl | input-lanjian | 2.1 ± 0.4 | 1.4 | 3.7 | 1.02 ± 0.23 |
| lanjian | input-lanjian | 2.4 ± 0.3 | 1.5 | 3.1 | 1.16 ± 0.23 |
| lanjian | input-mattcl | 2.5 ± 0.3 | 1.6 | 3.9 | 1.18 ± 0.23 |
| lanjian | input-kcen | 2.5 ± 0.3 | 1.6 | 3.3 | 1.20 ± 0.23 |
| kcen | input-lanjian | 4.3 ± 0.4 | 3.5 | 5.9 | 2.05 ± 0.37 |
| kcen | input-mattcl | 4.5 ± 0.4 | 3.8 | 6.6 | 2.18 ± 0.40 |
| kcen | input-kcen | 4.7 ± 0.5 | 3.9 | 7.8 | 2.24 ± 0.41 |
| mattcl-py | input-kcen | 31.3 ± 0.9 | 30.5 | 34.7 | 14.98 ± 2.37 |
| mattcl-py | input-lanjian | 31.3 ± 0.7 | 30.2 | 34.0 | 14.99 ± 2.36 |
| mattcl-py | input-mattcl | 31.4 ± 0.9 | 30.3 | 34.7 | 15.04 ± 2.38 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6378826667552</pre>|<pre>6413328569890</pre>|
|input-lanjian|<pre>6401092019345</pre>|<pre>6431472344710</pre>|
|input-mattcl|<pre>6349606724455</pre>|<pre>6376648986651</pre>|