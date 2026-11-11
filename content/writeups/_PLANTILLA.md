---
title: "HTB: NombreDeLaMáquina"
date: 2026-08-20
draft: true
platform: "HackTheBox"
os: "Linux"
difficulty: "Medium"
tags: ["hackthebox", "linux", "web", "privesc"]
summary: "Una línea que resuma el camino: 'SSTI en un panel interno lleva a RCE; escalada vía un binario SUID mal configurado.'"
---

> **Máquina retirada.** Este writeup se publicó después de que la máquina saliera
> de rotación activa, conforme a los términos de servicio de la plataforma.

## Resumen

Dos o tres frases con el camino completo, para quien solo quiera el mapa:

1. **Foothold** — [vulnerabilidad] en [servicio] → RCE como `www-data`.
2. **Movimiento lateral** — credenciales reutilizadas en [ubicación] → usuario `x`.
3. **Escalada** — [misconfiguración] → `root`.

---

## Reconocimiento

```bash
nmap -sC -sV -oA scans/inicial 10.10.11.X
```

```
PORT   STATE SERVICE VERSION
22/tcp open  ssh     OpenSSH 8.9p1
80/tcp open  http    nginx 1.18.0
```

**Qué me dice esto:** [Interpreta, no transcribas. La versión de OpenSSH sugiere
Ubuntu 22.04, lo cual descarta ciertos exploits de kernel. Solo dos puertos
significa que la superficie está en el web.]

### Enumeración web

[Qué buscaste y por qué. Directorios, subdominios, tecnología del stack.]

---

## Callejones sin salida

Esta sección es la que hace que un writeup valga la pena. Documenta lo que
intentaste y **por qué lo descartaste**:

- **Probé X.** Falló porque [razón técnica]. Lo descarté cuando vi [evidencia].
- **Asumí Y durante 40 minutos.** El error fue [qué asunción estaba mal].

---

## Foothold

[La vulnerabilidad. Explica *por qué* existe, no solo cómo se explota.]

```bash
# el payload / la petición
```

**Por qué funciona:** [Mecanismo. Si es una inyección, qué no se está sanitizando
y en qué contexto se interpreta.]

Shell obtenida:

```bash
nc -lvnp 4444
```

> Flag de usuario: `[captura de pantalla con la flag parcialmente tapada, o simplemente omítela]`

---

## Escalada de privilegios

[Enumeración post-explotación → el vector → root.]

**Por qué funciona:** [Mecanismo.]

---

## Remediación

La sección que te separa del 90% de los writeups. Para cada hallazgo:

| Hallazgo | Severidad | Remediación |
|---|---|---|
| [Vulnerabilidad del foothold] | Alta | [Cómo se arregla en concreto: parámetro, configuración, versión] |
| [Vector de escalada] | Media | [Corrección] |

---

## Qué me llevo

Una o dos frases honestas sobre lo que aprendiste o dónde perdiste tiempo.
Esto se lee como madurez técnica, no como debilidad.
