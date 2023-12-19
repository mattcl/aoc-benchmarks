# Day 18 benchmarks

[link to problem](https://adventofcode.com/2023/day/18)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2023)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 18)

- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [µs] | Min [µs] | Max [µs] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-mattcl | 853.7 ± 182.2 | 137.2 | 1061.1 | 1.00 |
| mattcl | input-pting | 900.6 ± 133.8 | 293.4 | 1661.6 | 1.05 ± 0.27 |
| mattcl-py | input-pting | 14337.0 ± 436.9 | 13572.5 | 17270.2 | 16.79 ± 3.62 |
| pting | input-pting | 14678.1 ± 659.0 | 13320.8 | 17858.6 | 17.19 ± 3.75 |
| mattcl-py | input-mattcl | 14920.3 ± 710.0 | 14036.7 | 19247.9 | 17.48 ± 3.82 |
| pting | input-mattcl | 15301.7 ± 1995.1 | 14183.3 | 41737.4 | 17.92 ± 4.48 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-mattcl|<pre>39194</pre>|<pre>78242031808225</pre>|
|input-pting|<pre>62573</pre>|<pre>54662804037719</pre>|