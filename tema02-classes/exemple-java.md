---
layout: default
title: 2. Exemple Java
parent: Tema 2 · Classes i Objectes
nav_order: 2
---

# Exemple Java
```java
public class Alumne {
    private String nom;
    private int edat;

    public Alumne(String nom, int edat){
        this.nom = nom;
        this.edat = edat;
    }

    public String getNom(){ return nom; }
    public int getEdat(){ return edat; }
}
```