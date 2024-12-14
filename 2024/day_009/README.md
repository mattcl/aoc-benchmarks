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
| mattcl | input-kcen | 2.2 ± 0.4 | 1.4 | 3.9 | 1.00 |
| mattcl | input-mattcl | 2.2 ± 0.3 | 1.4 | 3.6 | 1.00 ± 0.23 |
| mattcl | input-lanjian | 2.2 ± 0.4 | 1.3 | 3.6 | 1.02 ± 0.24 |
| lanjian | input-lanjian | 2.3 ± 0.5 | 0.9 | 6.0 | 1.06 ± 0.30 |
| lanjian | input-mattcl | 2.4 ± 0.3 | 1.5 | 4.5 | 1.11 ± 0.24 |
| lanjian | input-kcen | 2.5 ± 0.4 | 1.5 | 4.6 | 1.12 ± 0.25 |
| kcen | input-lanjian | 4.4 ± 0.4 | 3.7 | 6.0 | 1.98 ± 0.37 |
| kcen | input-mattcl | 4.7 ± 0.5 | 3.8 | 7.8 | 2.15 ± 0.43 |
| kcen | input-kcen | 4.8 ± 0.4 | 4.0 | 6.3 | 2.17 ± 0.40 |
| mattcl-py | input-lanjian | 31.4 ± 0.9 | 30.1 | 34.2 | 14.24 ± 2.40 |
| mattcl-py | input-kcen | 31.5 ± 0.8 | 29.7 | 34.8 | 14.25 ± 2.40 |
| mattcl-py | input-mattcl | 31.6 ± 0.9 | 30.7 | 34.4 | 14.34 ± 2.42 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6378826667552</pre>|<pre>6413328569890</pre>|
|input-lanjian|<pre>6401092019345</pre>|<pre>6431472344710</pre>|
|input-mattcl|<pre>6349606724455</pre>|<pre>6376648986651</pre>|