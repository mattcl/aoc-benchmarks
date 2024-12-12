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
| mattcl | input-kcen | 2.1 ± 0.4 | 0.9 | 3.4 | 1.00 |
| mattcl | input-mattcl | 2.2 ± 0.3 | 1.4 | 3.5 | 1.02 ± 0.24 |
| mattcl | input-lanjian | 2.2 ± 0.3 | 1.3 | 2.9 | 1.03 ± 0.24 |
| lanjian | input-kcen | 2.5 ± 0.3 | 1.6 | 3.4 | 1.19 ± 0.24 |
| lanjian | input-lanjian | 2.5 ± 0.3 | 1.6 | 4.0 | 1.19 ± 0.25 |
| lanjian | input-mattcl | 2.5 ± 0.3 | 1.5 | 4.6 | 1.19 ± 0.27 |
| kcen | input-lanjian | 4.5 ± 0.5 | 3.7 | 8.3 | 2.09 ± 0.44 |
| kcen | input-mattcl | 4.7 ± 0.5 | 4.0 | 8.4 | 2.19 ± 0.47 |
| kcen | input-kcen | 4.8 ± 0.4 | 3.9 | 6.5 | 2.27 ± 0.44 |
| mattcl-py | input-kcen | 31.7 ± 0.8 | 30.5 | 34.8 | 14.89 ± 2.69 |
| mattcl-py | input-lanjian | 31.9 ± 0.9 | 30.5 | 34.8 | 14.95 ± 2.71 |
| mattcl-py | input-mattcl | 31.9 ± 1.2 | 30.6 | 36.5 | 14.99 ± 2.74 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6378826667552</pre>|<pre>6413328569890</pre>|
|input-lanjian|<pre>6401092019345</pre>|<pre>6431472344710</pre>|
|input-mattcl|<pre>6349606724455</pre>|<pre>6376648986651</pre>|