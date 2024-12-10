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
- [mattcl](https://github.com/mattcl/aoc2024) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2024-py) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-mattcl | 2.1 ± 0.3 | 1.3 | 3.5 | 1.00 |
| mattcl | input-kcen | 2.1 ± 0.3 | 1.3 | 2.8 | 1.00 ± 0.22 |
| kcen | input-mattcl | 4.4 ± 0.4 | 3.6 | 7.4 | 2.09 ± 0.40 |
| kcen | input-kcen | 4.6 ± 0.6 | 3.8 | 7.8 | 2.16 ± 0.45 |
| mattcl-py | input-kcen | 31.5 ± 0.7 | 29.9 | 34.2 | 14.83 ± 2.44 |
| mattcl-py | input-mattcl | 31.6 ± 1.0 | 30.3 | 35.0 | 14.88 ± 2.47 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-kcen|<pre>6378826667552</pre>|<pre>6413328569890</pre>|
|input-mattcl|<pre>6349606724455</pre>|<pre>6376648986651</pre>|