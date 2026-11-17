# RoboCupJunior Soccer 2027: Scoring and Team Preparation

Web version of the redrafted 2027 scoring rules, in the same format as the official
[soccer rules site](https://robocup-junior.github.io/soccer-rules/master/scoring.html).

**Status: draft, awaiting committee approval.**

- `scoring.adoc` is the source. It is written as a drop-in replacement for `scoring.adoc`
  in [robocup-junior/soccer-rules](https://github.com/robocup-junior/soccer-rules).
- `index.html` is the rendered page, built with the same Asciidoctor image the official site uses:

```bash
docker run --rm -v "$PWD":/documents asciidoctor/docker-asciidoctor asciidoctor -o index.html scoring.adoc
```
