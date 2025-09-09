# 📚 Apresentação BIM1 — 2025B  
Repositório criado pelo **GitHub Classroom**

---

## PARTE PRÁTICA
 Inicialmente tive dificuldade para acessar os programas, mas após instalar corretamente as bibliotecas, não houve problemas. A instalação é bem simples:
 
 cabal update
 
 cabal install --lib scotty wai-extra random text

Abaixo mostro a execução dos exemplos de aplicações web em Haskell:

---

### 🔹 Hello Scotty (exemplo mínimo)
[📎 Vídeo demonstrativo](https://github.com/user-attachments/assets/14940bd5-4044-4263-8917-850f57d48b21)

O programa abre um servidor web simples na porta 3000 e mostra a mensagem "Hello Haskell web service!" na tela ao ser acessado na rota /hello.

---

### 🔹 Random Advice
[📎 Vídeo demonstrativo](https://github.com/user-attachments/assets/d654e244-552e-4542-9a76-3c78e19b484b)

Esse programa responde com conselhos aleatórios cada vez que o servidor é reiniciado, na rota /advice. O vídeo mostra as possíveis respostas do programa.

---

### 🔹 Random Advice JSON
<img width="706" height="559" alt="Captura de tela Random Advice JSON" src="https://github.com/user-attachments/assets/f1d4ac8a-267a-4e0a-932c-e2b34e339045" />

Bem semelhante ao programa anterior, mas nesse caso os "conselhos" já aparecem formatados em JSON.

---

### 🔹 Poi Service
<img width="732" height="455" alt="Captura de tela Poi Service 1" src="https://github.com/user-attachments/assets/7faf277e-e647-447e-a7bd-8c1203fd103b" />
<img width="760" height="1008" alt="Captura de tela Poi Service 2" src="https://github.com/user-attachments/assets/798c27ac-59dd-4fe5-ab80-653f4164ac5e" />

Esse programa sobe um servidor web que fornece informações sobre POIs da UFSM (semelhante a um programa visto anteriormente) em JSON: retorna um POI específico, Restaurante Universitário em /poi, e a lista completa em /poilist. 

Também temos a opção /near/:lat/:lon, que recebe uma latitude e longitude na URL e retorna os POIs que estão a até 1,5 km de distância usando uma fórmula para calcular distâncias, nesse caso, ja temos um exemplo para teste dentro do proprio programa (/near/-29.71689/-53.72968).

<img width="773" height="978" alt="image" src="https://github.com/user-attachments/assets/aed6dada-1d53-46ff-b0e3-cf358f36da6b" />

---

## FONTES:
Material da matéria sobre a biblioteca Scotty

https://www.haskell.org/cabal

https://hackage.haskell.org/package/scotty

https://youtu.be/psTTKGj9G6Y?si=5CK4wZ3iszF9aQHc

---

