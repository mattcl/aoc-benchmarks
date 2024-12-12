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
| mattcl | input-mattcl | 2.0 ± 0.3 | 1.4 | 3.4 | 1.00 |
| mattcl | input-kcen | 2.1 ± 0.4 | 1.3 | 3.5 | 1.00 ± 0.24 |
| lanjian | input-mattcl | 2.4 ± 0.3 | 1.3 | 3.1 | 1.18 ± 0.24 |
| lanjian | input-kcen | 2.5 ± 0.3 | 1.5 | 3.7 | 1.20 ± 0.25 |
| kcen | input-mattcl | 3.7 ± 0.5 | 2.8 | 6.5 | 1.83 ± 0.37 |
| kcen | input-kcen | 3.8 ± 0.3 | 3.0 | 4.8 | 1.85 ± 0.33 |
| mattcl-py | input-kcen | 31.1 ± 0.7 | 29.8 | 34.3 | 15.21 ± 2.48 |
| mattcl-py | input-mattcl | 31.3 ± 0.9 | 30.2 | 34.7 | 15.29 ± 2.51 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6378826667552</pre>|<pre>6413328569890</pre>|
|input-mattcl|<pre>6349606724455</pre>|<pre>6376648986651</pre>|