---
title: Exercícios
nav_order: 25
---

## Exercícios

Neste semestre usaremos o **GitHub Classroom** juntamente com a ferramenta [**TKO**](https://github.com/senapk/tko), elaborada pelo Prof. Davi Sena, nas nossas atividades práticas.

Em sala de aula, utilizaremos o **GitHub Codespaces** como ambiente de desenvolvimento. Caso, você queria configurar o **tko** na sua própria máquina para não usar o **codespaces**,
<a href="https://github.com/senapk/tko?tab=readme-ov-file#instala%C3%A7%C3%A3o">siga as intruções contidas no repoistório do TKO</a>


### Lista de exercícios

<table>
 <thead>
    <tr>
        <th> Nome </th>
        <th> Data de entrega </th>
    </tr>
 </thead>
 <tbody>
{% assign atividades = site.atividades | sort: "numero" %}
{% for atividade in atividades %}
    <tr>
        <td> <a href="{{ atividade.link }}" target="_blank">{{ atividade.nome }}</a></td>
        <td> {{ atividade.prazo }} </td>
    </tr>
{% endfor %}
  </tbody>
</table>

