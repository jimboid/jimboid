## Hi there 👋

```python
class Jimboid:

    def __init__(self):
        self.username = 'jimboid'
        self.name = 'James Gebbie-Rayet'
        self.position = 'Biomolecular Simulation Group Leader'
        self.languages = ["Python", "C", "C++", "Fortran", "HTML", "PHP", "JS", "CSS"]
        self.technologies = ["AWS", "Azure", "Kubernetes", "Docker", 
                             "Linux", "SQL", "Redis", "CUDA", "MPI", "OpenMP"]

    def __str__(self):
        return f'{self.name} | {self.position}'


if __name__ == '__main__':
    me = Jimboid()
    print(me)
```

<div align="center">
  <picture>
    <source
      media="(prefers-color-scheme: dark)"
      srcset="./profile/stats-dark.svg">
    <img
      width="400"
      src="./profile/stats-light.svg"
      alt="GitHub statistics">
  </picture>

  <picture>
    <source
      media="(prefers-color-scheme: dark)"
      srcset="./profile/streak-dark.svg">
    <img
      width="425"
      src="./profile/streak-light.svg"
      alt="GitHub contribution streak">
  </picture>
</div>
