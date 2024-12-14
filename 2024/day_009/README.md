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
| mattcl | input-mattcl | 2.2 ± 0.4 | 1.3 | 3.5 | 1.00 |
| mattcl | input-lanjian | 2.3 ± 0.4 | 1.4 | 3.6 | 1.03 ± 0.23 |
| mattcl | input-kcen | 2.3 ± 0.4 | 1.5 | 3.5 | 1.04 ± 0.24 |
| lanjian | input-mattcl | 2.4 ± 0.3 | 1.4 | 3.1 | 1.09 ± 0.22 |
| lanjian | input-kcen | 2.5 ± 0.3 | 1.6 | 4.0 | 1.14 ± 0.23 |
| lanjian | input-lanjian | 2.5 ± 0.3 | 1.5 | 4.3 | 1.15 ± 0.24 |
| kcen | input-lanjian | 4.5 ± 0.5 | 3.7 | 7.4 | 2.05 ± 0.40 |
| kcen | input-mattcl | 4.8 ± 0.6 | 3.9 | 8.3 | 2.18 ± 0.44 |
| kcen | input-kcen | 4.9 ± 0.5 | 3.9 | 7.7 | 2.22 ± 0.43 |
| mattcl-py | input-lanjian | 31.6 ± 0.9 | 30.5 | 34.8 | 14.42 ± 2.38 |
| mattcl-py | input-kcen | 31.6 ± 0.9 | 30.1 | 35.2 | 14.45 ± 2.38 |
| mattcl-py | input-mattcl | 31.7 ± 1.0 | 30.5 | 34.6 | 14.47 ± 2.39 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6378826667552</pre>|<pre>6413328569890</pre>|
|input-lanjian|<pre>6401092019345</pre>|<pre>6431472344710</pre>|
|input-mattcl|<pre>6349606724455</pre>|<pre>6376648986651</pre>|