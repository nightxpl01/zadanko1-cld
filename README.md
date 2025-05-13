# Zadanko 1

## Autor: Michał Małysz GR.6

## GitHub: 
https://github.com/nightxpl01/zadanko1-cld

## DockerHub: 
https://hub.docker.com/r/mikhaelo/zadanko1

---

## Polecenia:

---

docker build -t mikhaelo/zadanko1 .

---

docker run -d -p 8069:8069 --name zadanko1_mm -e API_KEY=26b964c3980c2aa90c78114181364841 mikhaelo/zadanko1

---

docker logs zadanko1_mm

---

docker image inspect mikhaelo/zadanko1

---

docker history mikhaelo/zadanko1

---
