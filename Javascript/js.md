# Questões de Javascript

1. Explique como a keyword `this` funciona no Javascript.
<details>
<summary>1. Resposta</summary>
<br>
  
A keyword `this` se refere ao objeto ao qual ela pertence. Ou seja, ela possui significado diferente dependendo de onde ela é usada.

Por exemplo, se chamarmos a keyword `this` de forma isolada, ela vai se referir ao objeto global.

No caso do browser, o objeto global é o objeto `window`:

![image](https://user-images.githubusercontent.com/8127858/137424309-5b8e2749-5f72-4811-a806-bb7fc319861f.png)

**Exemplo 2:** 

No caso abaixo, temos um método (função dentro de objeto) chamado `fullname`. 

E nesse contexto o `this` se refere ao "dono" do método, que nesse exemplo é o objeto `pessoa`.

![image](https://user-images.githubusercontent.com/8127858/137424333-281e0369-9d6f-4729-91c6-b9e7ad661ad7.png)
</details>
