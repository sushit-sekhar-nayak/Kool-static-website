If you want to buil the static web hosting with nginx
```bash
docker build -t kool:v1 . 
```
 
for running,
```bash
docker run -d -p 130:80 --name kool kool:v1
```
Output will be like this: 
---
![Docker Architecture](./image.png)
---

