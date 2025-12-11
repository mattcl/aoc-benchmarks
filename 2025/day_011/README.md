# Day 11 benchmarks

[link to problem](https://adventofcode.com/2025/day/11)

The following benchmarks are auto-generated via
[hyperfine](https://github.com/sharkdp/hyperfine) by a CI system running on
dedicated hardware. As per the hyperfine documentation, results may be
inaccurate for times < 5 ms. These benchmarks represent the total time to read,
parse, and solve the given inputs, and, as such, some variation is expected due
to IO and other factors.

[CI pipeline](http://ci.papercode.net:8080/teams/main/pipelines/aoc2025)

[Benchmark web UI](https://aoc.ancalagon.black)


## Participants (with solutions for day 11)

- [lanjian](https://github.com/lanjian/aoc-2025) (rust)
- [mattcl](https://github.com/mattcl/aoc2025) (rust)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [µs] | Min [µs] | Max [µs] | Relative |
|:---|:---|---:|---:|---:|---:|
| mattcl | input-mattcl | 900.5 ± 189.7 | 0.0 | 1548.2 | 1.00 |
| mattcl | input-lanjian | 910.6 ± 146.1 | 368.5 | 1402.6 | 1.01 ± 0.27 |
| lanjian | input-lanjian | 995.1 ± 180.5 | 83.1 | 1655.4 | 1.11 ± 0.31 |
| lanjian | input-mattcl | 1034.0 ± 211.1 | 118.7 | 1712.2 | 1.15 ± 0.34 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>670</pre>|<pre>332052564714990</pre>|
|input-mattcl|<pre>585</pre>|<pre>349322478796032</pre>|