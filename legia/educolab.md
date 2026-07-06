---
layout: single
title: "Projeto EduColab"
sidebar:
    nav: "legia"
---

O projeto **EduColab** tem como objetivo principal a disseminação do seu **Sistema de Recomendação Educacional** para promover a colaboração em fóruns de discussão do Moodle. Este projeto está inserido na Chamada Capes 3/2025: InovaEDUCAÇÃO e faz parte do **Fórum Permanente de Letramento, Ética e Governança em Inteligência Artificial – LEGIA**.

<div style="text-align: center; margin: 2em 0; padding: 1.5em; background-color: #f8f9fa; border-radius: 8px; border-left: 5px solid #28a745; box-shadow: 0 4px 6px rgba(0,0,0,0.05);">
  <h3 style="margin-top: 0;">Conheça nosso Ambiente de Aprendizagem</h3>
  <p>Acesse agora mesmo a plataforma do curso e participe das discussões e dinâmicas promovidas pelo projeto.</p>
  <a href="http://100.49.176.103/login/index.php" class="btn btn--success btn--large" target="_blank" rel="noopener noreferrer">
    <i class="fas fa-graduation-cap"></i> Acessar o Curso EduColab
  </a>
</div>

## Contextualização

O grande desafio na educação mediada por tecnologia é **facilitar a colaboração e o aprendizado entre os estudantes**. Os fóruns de discussão são frequentemente utilizados como estratégia para promover essa colaboração. 

Nesse contexto, surgiu o **EduColab**, iniciativa do Prof. Dr. Antônio Justiniano como resultado de sua tese de doutorado. O EduColab é um Sistema de Recomendação Educacional (SRE) que utiliza a Análise Conversacional (AC) para medir a colaboração entre alunos e realizar recomendações em fóruns de discussão de um Ambiente Virtual de Aprendizagem (AVA). O projeto também inclui a prototipação de um plugin, resultado do Trabalho de Conclusão de Curso do estudante Gabriel Lima, que integra o Moodle a este SRE.

## Principais Funcionalidades

A integração da ferramenta com o Moodle através de um plugin oferece as seguintes funcionalidades principais:

- **Cadastro:** Permite que o professor cadastre facilmente os fóruns que deseja monitorar e acompanhar.
- **Análise Manual:** O professor pode solicitar a análise das mensagens de um fórum cadastrado a qualquer momento, o que irá gerar e enviar recomendações por e-mail para os estudantes.
- **Análise Automática:** Possibilita a definição de uma frequência de análise (diária, semanal, mensal, etc.), garantindo que as interações sejam avaliadas periodicamente sem a necessidade de ação manual.
- **Personalização:** O plugin permite a edição do e-mail de confirmação ou de recomendação, aceitando variáveis dinâmicas resolvidas pelo SRE.

## Desenvolvimento e Tecnologias

O ecossistema do EduColab é dividido em três frentes de desenvolvimento:

1. **Plugin (Bloco do Moodle):** Desenvolvido com PHP, HTML (Mustache), CSS e JavaScript.
2. **Sistema de Recomendação (SRE):** Desenvolvido utilizando Python.
3. **API (Comunicação):** Uma API REST em Node.js com Express que faz a ponte entre o plugin e o motor do SRE.

## Equipe do Projeto

O projeto conta com a dedicação e o trabalho conjunto da seguinte equipe:

### Infraestruturas Moodle, plugin e página web do Legia
- Raimundo Claudio da Silva Vasconcelos
- Pedro Paulo Martins de Andrade
- Giovanni Lucas Oliveira da Silva

### Materiais de apoio
*Foco na produção de vídeos, tutoriais passo a passo, guias de uso e curso de curta duração com certificação.*
- Thiago Batista Amorim
- Joyce Vieira de Castro Marra
- João Caio de Oliveira Lins

### Implementação, teste, prospecção e validação do EduColab
- Antônio Justiniano de Moraes Neto
- Gabriel Junio Castro de Lima
- Henrico Costa Correia
- Igor de Oliveira Moura

### Identidade visual: gráfica; página web e plugin
- Raimundo Claudio da Silva Vasconcelos
- Thiago Batista Amorim
- Antônio Justiniano de Moraes Neto
- João Caio de Oliveira Lins
- Igor de Oliveira Moura
- Pedro Paulo Martins de Andrade

