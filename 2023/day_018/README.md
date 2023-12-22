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

- [lanjian](https://github.com/lanjian/aoc-2023) (rust)
- [mattcl](https://github.com/mattcl/aoc2023) (rust)
- [mattcl-py](https://github.com/mattcl/aoc2023-py) (python)
- [pting](https://github.com/pting/aoc2023) (python)


## Benchmarks with officially generated inputs

| Participant | Input | Mean [µs] | Min [µs] | Max [µs] | Relative |
|:---|:---|---:|---:|---:|---:|
| lanjian | input-pting | 825.2 ± 175.3 | 133.3 | 1596.8 | 1.00 |
| mattcl | input-lanjian | 844.9 ± 169.9 | 91.5 | 1051.6 | 1.02 ± 0.30 |
| mattcl | input-pting | 864.9 ± 167.4 | 129.8 | 1128.7 | 1.05 ± 0.30 |
| lanjian | input-mattcl | 865.4 ± 146.3 | 204.3 | 1058.1 | 1.05 ± 0.28 |
| lanjian | input-lanjian | 866.4 ± 143.1 | 154.5 | 1223.1 | 1.05 ± 0.28 |
| mattcl | input-mattcl | 887.9 ± 157.1 | 165.3 | 1095.1 | 1.08 ± 0.30 |
| mattcl-py | input-pting | 14478.9 ± 644.5 | 13522.1 | 17643.1 | 17.55 ± 3.81 |
| mattcl-py | input-lanjian | 14540.8 ± 566.5 | 13513.7 | 17530.8 | 17.62 ± 3.81 |
| pting | input-pting | 14689.3 ± 600.0 | 13536.4 | 17693.3 | 17.80 ± 3.85 |
| pting | input-lanjian | 14765.9 ± 625.3 | 13724.6 | 18073.7 | 17.89 ± 3.88 |
| pting | input-mattcl | 15110.9 ± 528.0 | 14070.1 | 17660.9 | 18.31 ± 3.94 |
| mattcl-py | input-mattcl | 15236.5 ± 3483.0 | 13844.5 | 62838.2 | 18.47 ± 5.76 |


## Inputs -> Solutions

| Input | Part One | Part Two |
|:---|:---|:---|
|input-lanjian|<pre>50603</pre>|<pre>96556251590677</pre>|
|input-mattcl|<pre>39194</pre>|<pre>78242031808225</pre>|
|input-pting|<pre>62573</pre>|<pre>54662804037719</pre>|