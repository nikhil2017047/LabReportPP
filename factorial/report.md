[Home of Lab Report](../lab.html)

# Program Ex 01: Change it

## Flow chart

### Sample flow chart

You may find biggest among three numbers, by comparing systematically two numbers at a time, as shown in flowchart below:

[![](https://mermaid.ink/img/eyJjb2RlIjoiZ3JhcGggVERcbjEoW1N0YXJ0XSkgLS0-IDJbXCJhIOKGkCB4PGJyLz4gYiDihpAgeTxici8-YyDihpAgejxici8-XCJdXG4yIC0tPiAze2EgPiBifVxuMyAtLT58WWVzfCA0e2EgPiBjfVxuNCAtLT58Tm98IDhbL091dHB1dCBjL11cbjQgLS0-IHxZZXN8IDZbL091dHB1dCBhL11cbjMgLS0-fE5vfCA1e2IgPiBjfVxuNSAtLT4gfE5vfCA2XG41IC0tPiB8WWVzfCA3Wy9PdXRwdXQgYi9dXG43IC0tPiA5KFtTdG9wXSlcbjYgLS0-IDlcbjggLS0-IDlcbiIsIm1lcm1haWQiOnsidGhlbWUiOiJkZWZhdWx0In0sInVwZGF0ZUVkaXRvciI6ZmFsc2V9)](https://mermaid-js.github.io/mermaid-live-editor/#/edit/eyJjb2RlIjoiZ3JhcGggVERcbjEoW1N0YXJ0XSkgLS0-IDJbXCJhIOKGkCB4PGJyLz4gYiDihpAgeTxici8-YyDihpAgejxici8-XCJdXG4yIC0tPiAze2EgPiBifVxuMyAtLT58WWVzfCA0e2EgPiBjfVxuNCAtLT58Tm98IDhbL091dHB1dCBjL11cbjQgLS0-IHxZZXN8IDZbL091dHB1dCBhL11cbjMgLS0-fE5vfCA1e2IgPiBjfVxuNSAtLT4gfE5vfCA2XG41IC0tPiB8WWVzfCA3Wy9PdXRwdXQgYi9dXG43IC0tPiA5KFtTdG9wXSlcbjYgLS0-IDlcbjggLS0-IDlcbiIsIm1lcm1haWQiOnsidGhlbWUiOiJkZWZhdWx0In0sInVwZGF0ZUVkaXRvciI6ZmFsc2V9)

## Markdown code

Markdown used at [MerMaid](https://mermaid-js.github.io/mermaid-live-editor/).

```
graph TD
1([Start]) --> 2["a ← x<br/> b ← y<br/>c ← z<br/>"]
2 --> 3{a > b}
3 -->|Yes| 4{a > c}
4 -->|No| 8[/Output c/]
4 --> |Yes| 6[/Output a/]
3 -->|No| 5{b > c}
5 --> |No| 6
5 --> |Yes| 7[/Output b/]
7 --> 9([Stop])
6 --> 9
8 --> 9
```

## Source file/s

```
src/.
└── main.c

0 directories, 1 file
```

---

## Compilation

```
xmake

[ 50%]: ccache compiling.release src/main.c
[ 75%]: linking.release factorial
[100%]: build ok!

```

## Execution
```
xmake run

hello world!

```

### Known Bugs and/or Errors:

List all the known limitations / bugs and / or errors of your program.

After extensively testing your program, you should be aware of (nearly) every issue it has. How does your program handle bad input? How does your program handle edge cases? This section is a space for full-disclosure; what's wrong with your program?

### Lessons Learned:

1. What went well
1. What you would do differently next time
1. How the exercise might be revised to make it clearer/more satisfying
1. What the faculty members might have done differently to promote learning
